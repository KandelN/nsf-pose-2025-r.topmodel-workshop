# Physically-based hydrologic modeling using GRASS GIS r.topmodel

This project hosts the materials for the [NSF POSE 2025 r.topmodel workshop](https://workshop.isnew.info/nsf-pose-2025-r.topmodel/) in a Quarto webpage format. The repository is structured to provide both a multi-page website and a single-page version of the workshop content.  

## Project Structure  

- **Main Webpage**: The primary workshop materials are rendered into a multi-page website.  
- **Single-Page Directory**: Contains the quarto code for rendering a single-page version of the workshop materials.  
- **Single-Quarto Directory**: Includes a self-contained single .qmd file that represents the entire workshop, which can be rendered into a single HTML page.

## Compiling the Quarto Files  

### Multi-Page Website  
To compile the main workshop webpage, run the following command:  
```bash  
quarto render index.qmd  
```  
The output will be generated in the `_output` folder, containing the compiled HTML files for the multi-page website.  

### Single-Page Version  
To compile the single-page version of the workshop materials, run the following command:  
```bash  
quarto render single-page/index.qmd  
```  
The output will be a single `index.html` file located directly in the `single-page` directory.  

### Single-Quarto File  
To compile the entire workshop into a single HTML file using the self-contained Quarto file,  run the following command:  
```bash  
quarto render single-qmd/r.topmodel.qmd    
```  
The output will be a single `r.topmodel.html` file located directly in the `single-qmd` directory.  

## Resources and References
- **Workshop Website**: [NSF POSE 2025 r.topmodel Workshop](https://workshop.isnew.info/nsf-pose-2025-r.topmodel/)  
- **Source Repository**: [GitHub - nsf-pose-2025-r.topmodel-workshop](https://github.com/HuidaeCho/nsf-pose-2025-r.topmodel-workshop)  
- **Quarto Documentation**: [Quarto Official Documentation](https://quarto.org/docs/get-started/)  
