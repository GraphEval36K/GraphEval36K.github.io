# academic_page_builder

> A simple and customizable tool for building professional web pages to showcase your academic papers. 

> This repository helps researchers quickly create websites for their publications, with minimal effort and setup.

> The tool enables easy modification and deployment via GitHub Pages.

## Demo page
- [View the demo page](https://chen-zichen.github.io/academic_page_builder/)


## Structure
```
academic_page_builder/
│
├── index.md                  # The main page
├── _config.yml               # Jekyll config for the site
├── _layouts/                 # Custom HTML layout templates
│   └── project_page.html     # Basic layout to wrap around markdown content
├── static/                   # Directory for static files like images, CSS, JS
│   ├── css/
│   │   ├── bulma.min.css     # Bulma CSS framework
│   │   └── index.css         # The styles for paper webpages
│   ├── js/
│   │   ├── fontawesome.all.min.js  # For icons, if needed
│   │   └── index.js          # Custom JS for the site
│   └── image/                # Images for the site
├── README.md                 # Documentation
├── _site/...                 # The compiled site 
└── .gitignore                # Ignore unnecessary files
```

## How to use

1. **Clone the repository:**
   ```bash
   git clone https://github.com/chen-zichen/academic_page_builder.git

2. **Preview the site locally:**
- Make sure you have Jekyll installed. If not, install it using `gem install jekyll bundler`.
- Run the following command in the repository's root directory to serve the site locally:
     ```bash
     jekyll serve
     ```
 - Open your browser and go to `http://localhost:4000/` to see the site.

3. **Modify the `index.md` file**:
- **Title**: Set your paper's title.
- **Authors**: Update with the names of the authors.
- **Affiliations**: Mention the authors' affiliations.
- **Paper**: Provide a link to the PDF of the paper. [optional]
- **Video**: Add a link to your demo video (e.g., YouTube). [optional]
- **Code**: Provide a link to the code repository. [optional]
- **Data**: Optionally, include a dataset link. [optional]
- **Description**: Add a brief abstract or summary.

4. **Add your research content**:
- Update sections such as **Abstract/Introduction**, **Key Contributions**, **Methodology**, and **VisualResults**.
- Include any images by placing them in the `static/image` directory and referencing them in the markdown.
- Embed video demos using the provided `<iframe>` example in the **Video Demo** section.

5. **Deploy the site**:
- Push the changes to the `main` branch.
- Enable GitHub Pages in your repository settings under the **Pages** section, choosing the `main` branch as the source.
- For more deployment information, refer to the [GitHub Pages documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site).

6. **Customize styles**:
- You can modify the CSS in the `static/css` directory if needed.

## License
This project is licensed under the CC BY-SA 4.0 License - see the [LICENSE](LICENSE) file for details. If you use this project, please provide a link to this repository. 
