# MIT Centennial Portal

A single-page website concept for the **Myanmar Institute of Theology (MIT)** centennial (1927–2027), focused on the Liberal Arts Program (LAP).

Everything lives in `index.html`: React 18, React Router and Tailwind CSS load from CDNs, and Babel compiles the JSX in the browser, so there is no build step.

## Pages

- **Home**: centennial hero, president's spotlight, legacy in numbers, academic divisions, admissions notice
- **LAP Programs**: six undergraduate majors, tuition, and the 2026–2027 admissions timetable
- **About Us**: mission and vision, a leadership carousel, and accreditation
- **Events & Activities**: filterable campus events and the chapel schedule
- **Contact Us**: department directory, inquiry form, document downloads, and campus map

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
npx http-server . -p 5174
```
