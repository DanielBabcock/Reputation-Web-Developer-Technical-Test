# Reputation Tech Challenge: using my in-work project skeleton

- This is a skeleton framework for projects built with the concept of tidly scaling is based off the Atomic Design theory by Brad Frost.
- This Atomic-esque Design structure is not a fit for every project.

## Notes (TODO list, Flaws, Plans):

- FLAWs:
- - Scalability and DRY is not being followed.
- - Meshing three class name systems together (widgets, bootstrap, and my skeleton) is a little messy here as my skeleton should be brought inline with naming conventions from Reputation.
- PLANS:
- - Re-design elements to work with Handlebars as partials and templates, see if possible to use handlebars to componentize patterns in Atomic stucture.
- - Devise scalable data structures
- TODO: Before further development learn more about the base product's code and design ecosystems, then re-write.

## Dev Commands:

<pre> 
  <code>
    sass --watch css-core/rep.scss:style.css
      &&
    http-server -p 8080
  </code>
</pre>

### File Tree:

- [assets/](./Babcock---Reputation-Web-Developer---Technical-Test/assets)
  - [data/](./Babcock---Reputation-Web-Developer---Technical-Test/assets/data)
  - [fonts/](./Babcock---Reputation-Web-Developer---Technical-Test/assets/fonts)
  - [images/](./Babcock---Reputation-Web-Developer---Technical-Test/assets/images)
- [css-core/](./Babcock---Reputation-Web-Developer---Technical-Test/css-core)
  - [core-variables.scss](./Babcock---Reputation-Web-Developer---Technical-Test/css-core/core-variables.scss)
  - [global-utilities.scss](./Babcock---Reputation-Web-Developer---Technical-Test/css-core/global-utilities.scss)
  - [grid.scss](./Babcock---Reputation-Web-Developer---Technical-Test/css-core/grid.scss)
  - [mixins.scss](./Babcock---Reputation-Web-Developer---Technical-Test/css-core/mixins.scss)
  - [rep-reset.scss](./Babcock---Reputation-Web-Developer---Technical-Test/css-core/rep-reset.scss)
  - [rep.scss](./Babcock---Reputation-Web-Developer---Technical-Test/css-core/rep.scss)
  - [typography.scss](./Babcock---Reputation-Web-Developer---Technical-Test/css-core/typography.scss)
- [js/](./Babcock---Reputation-Web-Developer---Technical-Test/js)
- [node_modules/](./Babcock---Reputation-Web-Developer---Technical-Test/node_modules)
- [patterns/](./Babcock---Reputation-Web-Developer---Technical-Test/patterns)
  - [atoms/](./Babcock---Reputation-Web-Developer---Technical-Test/patterns/atoms)
    - [buttons/](./Babcock---Reputation-Web-Developer---Technical-Test/patterns/atoms/buttons)
      - [buttons.scss](./Babcock---Reputation-Web-Developer---Technical-Test/patterns/atoms/buttons/buttons.scss)
  - [molecules/](./Babcock---Reputation-Web-Developer---Technical-Test/patterns/molecules)
    - [footer-health--simple/](./Babcock---Reputation-Web-Developer---Technical-Test/patterns/molecules/footer-health--simple)
      - [footer-health--simple.scss](./Babcock---Reputation-Web-Developer---Technical-Test/patterns/molecules/footer-health--simple/footer-health--simple.scss)
    - [nav-health--simple/](./Babcock---Reputation-Web-Developer---Technical-Test/patterns/molecules/nav-health--simple)
      - [nav-health--simple.scss](./Babcock---Reputation-Web-Developer---Technical-Test/patterns/molecules/nav-health--simple/nav-health--simple.scss)
    - [widgets/](./Babcock---Reputation-Web-Developer---Technical-Test/patterns/molecules/widgets)
      - [widgets.scss](./Babcock---Reputation-Web-Developer---Technical-Test/patterns/molecules/widgets/widgets.scss)
  - [organisms/](./Babcock---Reputation-Web-Developer---Technical-Test/patterns/organisms)
    - [card-doctor--hero/](./Babcock---Reputation-Web-Developer---Technical-Test/patterns/organisms/card-doctor--hero)
      - [card-doctor--hero.scss](./Babcock---Reputation-Web-Developer---Technical-Test/patterns/organisms/card-doctor--hero/card-doctor--hero.scss)
    - [card-doctor--info/](./Babcock---Reputation-Web-Developer---Technical-Test/patterns/organisms/card-doctor--info)
      - [card-doctor--info.scss](./Babcock---Reputation-Web-Developer---Technical-Test/patterns/organisms/card-doctor--info/card-doctor--info.scss)
  - [templates/](./Babcock---Reputation-Web-Developer---Technical-Test/patterns/templates)
    - [doctors/](./Babcock---Reputation-Web-Developer---Technical-Test/patterns/templates/doctors)
      - [doctors.html](./Babcock---Reputation-Web-Developer---Technical-Test/patterns/templates/doctors/doctors.html)
      - [doctors.js](./Babcock---Reputation-Web-Developer---Technical-Test/patterns/templates/doctors/doctors.js)
      - [doctors.scss](./Babcock---Reputation-Web-Developer---Technical-Test/patterns/templates/doctors/doctors.scss)
- [LICENSE](./Babcock---Reputation-Web-Developer---Technical-Test/LICENSE)
- [README.md](./Babcock---Reputation-Web-Developer---Technical-Test/README.md)
- [index.html](./Babcock---Reputation-Web-Developer---Technical-Test/index.html)
- [package-lock.json](./Babcock---Reputation-Web-Developer---Technical-Test/package-lock.json)
- [package.json](./Babcock---Reputation-Web-Developer---Technical-Test/package.json)
- [style.css](./Babcock---Reputation-Web-Developer---Technical-Test/style.css)
- [style.css.map](./Babcock---Reputation-Web-Developer---Technical-Test/style.css.map)

### Useful with IE bugs if needed:

<pre>
    <code>
        @media all and (-ms-high-contrast: none),
            (-ms-high-contrast: active) {
                // IE10+ CSS here // ie bug
                .targeted-class {
                    // do stuff here 
                }            
        }
    </code>
</pre>
