
## My Implementations

The following files reflect the implementation of technical functionalities and system-level logic:

### **Technical Functionalities**

| File/Directory    | Description                                          |
| ----------------- | ---------------------------------------------------- |
| `src/components/` | Reusable UI components with specific functionalities |
| `src/views/`      | Page-level components handling different routes      |
| `src/App.vue`     | Root component orchestrating layout and components   |

### **System-Level Logic**

| File/Directory        | Description                                     |
| --------------------- | ----------------------------------------------- |
| `src/router/index.js` | Defines routes with lazy-loaded components      |
| `src/main.js`         | Initializes Vue app with router and store       |
| `vite.config.js`      | Customized build configurations for performance |

---

## Framework & Boilerplate

These files are provided by the Vue.js framework or build tools:

| File/Directory | Description                                        |
| -------------- | -------------------------------------------------- |
| `public/`      | Static assets served directly (e.g., `index.html`) |
| `package.json` | Project metadata and dependency declarations       |

---

## 🚀 Performance Optimization Techniques

The following optimization techniques were implemented to improve the performance of the application:

- **Image Optimization (CDN & Dynamic Parameters):**  
  Reduced image sizes and served modern formats (WebP/AVIF) based on the client browser, improving Largest Contentful Paint (LCP).

- **JavaScript Minification:**  
  Removed unused code, shortened variable names, and stripped whitespace in production builds to reduce the bundle size and speed up parsing.

- **GZIP Compression:**  
  Compressed HTML, CSS, and JS assets during transfer to reduce load time and improve First Contentful Paint (FCP) and Speed Index.

- **Lazy Loading of Components (Code Splitting):**  
  Loaded Vue components on demand using dynamic imports, minimizing the initial bundle size and improving load performance.

- **Native Lazy Loading of Images:**  
  Delayed loading of images outside the viewport using the `loading="lazy"` attribute, enhancing LCP and perceived performance.


---

## Performance Profiling Tools

Tools used for monitoring and analyzing performance:

- **Chrome DevTools**: Performance tracing and scripting analysis.
- **Lighthouse**: Automated audits for performance, accessibility, and best practices.

---

## Installation & Development

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

