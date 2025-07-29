# The Timeless Magic of The Wine Windows 
An interactive scrollytelling project exploring the renaissance and modern revival of Florence's historic wine windows (Buchette del Vino).

## Project Overview

### What We Aimed to Accomplish

This project aimed to create an engaging, interactive web experience that tells the story of Florence's wine windows — small architectural features that have survived centuries and found new life during the COVID-19 pandemic. The goal was to combine historical research, data visualization, and modern web design to showcase how these 17th-century innovations remain relevant today.

### Key Findings

- **177 wine windows** officially documented in Florence's municipality  
- The **Santa Croce district** has the highest concentration  
- Wine windows experienced a remarkable revival during COVID-19 (e.g., *Vivoli Gelateria*)  
- The tradition has spread internationally (e.g., *Please Tell Me*, Brooklyn, NYC)  
- Originally used for **tax avoidance** and **social distancing** during plague outbreaks  

## Data Collection Process

### Primary Sources

1. **Associazione Culturale Buchette del Vino di Firenze**  
   - Official registry of authenticated wine windows  
   - Historical documentation and verification records  
   - [Association Website](https://buchettedelvino.org)

2. **Tuscany Region Open Data Portal**  
   - Geospatial data on wine window locations  
   - Historical district boundaries  
   - [Dataset Link](https://dati.toscana.it)

3. **Historical Archives**  
   - Francesco Rondinelli's *Relazione del contagio* (1634)  
   - James Fenimore Cooper's *Excursions in Italy* (1838)

### Data Gathering Methods

- Web scraping of the official wine windows registry  
- Manual georeferencing of historical maps  
- Field verification through street-level photography  
- Social media analysis using `#winewindowsflorence`


## Data Analysis Process

### Tools Used

- **Python** (`pandas`, `BeautifulSoup`) for data cleaning and scraping  
- **QGIS** for geospatial analysis and map creation  
- **Adobe Illustrator** for layout improvement and graphics  
- **Scrollama.js** for scrollytelling functionality

### Analysis Steps

1. **Data Cleaning**  
   - Standardized address formats  
   - Validated coordinates  
   - Removed duplicate entries  

2. **Spatial Analysis**  
   - Calculated wine window density by district  
   - Created heat maps  
   - Analyzed proximity to noble palaces  

3. **Visualization Development**  
   - Designed interactive evolution maps  
   - Built responsive layouts  
   - Implemented scroll-triggered animations  

## New Skills & Growth Areas

### Technical Achievements

- **Scrollama.js**: First use of scrollytelling with Scrollama  
- **Responsive Design**: Adaptive layouts for all devices  
- **Performance Optimization**: Lazy loading + image compression  
- **Accessibility**: Semantic HTML + ARIA labels

### Creative Growth

- **Visual Storytelling**: Combined narrative and data  
- **UX Design**: Smooth user flow with intuitive interaction  
- **Cultural Communication**: Made local heritage globally accessible  


## Future Enhancements

### Features We'd Like to Add

1. **3D Map Visualization**  
   - 3D Florence with wine window locations  
   - Requires: Three.js & 3D modeling

2. **Augmented Reality (AR) App**  
   - Find wine windows in real time  
   - Requires: AR dev tools & mobile framework

3. **User-Generated Content**  
   - Allow users to submit new wine windows  
   - Requires: Backend + auth system

4. **Multi-language Support**  
   - Italian, Spanish, French, German  
   - Requires: i18n framework

5. **Interactive Historical Timeline**  
   - Shows usage across centuries  
   - Requires: Further research + D3 expertise

### Data Enhancements

- Real-time integration of `#winewindowsflorence` posts  
- Partnership with local businesses for live status  
- Historical wine price data 
