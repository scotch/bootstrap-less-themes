# boostrap-less-themes

Provides theme files for use with Bootstrap less

## Install

```
bower install git://github.com/scotch/bootstrap-less-themes.git
```

## Example usage

`app.less`

```
// CSS Reset
@import "/vendor/bootstrap/less/reset.less";

// Theme variables
// Uncomment the theme you would like to use. Themes may include
// override.less files as well, so be sure to add the themes
// override.less file to the bottom of this file.

// Bootstrap default
// @import "/vendor/bootstrap-less-themes/themes/default/variables.less";

// Sapling default
@import "/vendor/bootstrap-less-themes/themes/sapling/variables.less";

// Core variables and mixins
@import "/vendor/bootstrap/less/mixins.less";

// Grid system and page structure
@import "/vendor/bootstrap/less/scaffolding.less";
@import "/vendor/bootstrap/less/grid.less";
@import "/vendor/bootstrap/less/layouts.less";

// Base CSS
@import "/vendor/bootstrap/less/type.less";
@import "/vendor/bootstrap/less/code.less";
@import "/vendor/bootstrap/less/forms.less";
@import "/vendor/bootstrap/less/tables.less";

// vendor: common
@import "/vendor/bootstrap/less/sprites.less";

@import "/vendor/font-awesome/less/font-awesome.less";

@import "/vendor/bootstrap/less/dropdowns.less";
@import "/vendor/bootstrap/less/wells.less";
@import "/vendor/bootstrap/less/component-animations.less";
@import "/vendor/bootstrap/less/close.less";

// vendor: Buttons & Alerts
@import "/vendor/bootstrap/less/buttons.less";
@import "/vendor/bootstrap/less/button-groups.less";
@import "/vendor/bootstrap/less/alerts.less"; // Note: alerts share common CSS with buttons and thus have styles in buttons.less

// vendor: Nav
@import "/vendor/bootstrap/less/navs.less";
@import "/vendor/bootstrap/less/navbar.less";
@import "/vendor/bootstrap/less/breadcrumbs.less";
@import "/vendor/bootstrap/less/pagination.less";
@import "/vendor/bootstrap/less/pager.less";

// vendor: Popovers
@import "/vendor/bootstrap/less/modals.less";
@import "/vendor/bootstrap/less/tooltip.less";
@import "/vendor/bootstrap/less/popovers.less";

// vendor: Misc
@import "/vendor/bootstrap/less/thumbnails.less";
@import "/vendor/bootstrap/less/media.less";
@import "/vendor/bootstrap/less/labels-badges.less";
@import "/vendor/bootstrap/less/progress-bars.less";
@import "/vendor/bootstrap/less/accordion.less";
@import "/vendor/bootstrap/less/carousel.less";
@import "/vendor/bootstrap/less/hero-unit.less";

// Componets: Footer
@import "/vendor/bootstrap-less-themes/themes/sapling/sticky-footer.less";

// Responsive
@import "/vendor/bootstrap/less/responsive-utilities.less";
@import "/vendor/bootstrap/less/responsive-1200px-min.less";
@import "/vendor/bootstrap/less/responsive-768px-979px.less";
@import "/vendor/bootstrap/less/responsive-767px-max.less";
@import "/vendor/bootstrap/less/responsive-navbar.less";

// AngularJS
@import "/vendor/bootstrap-less-themes/themes/angular/forms.less";

// Utility classes
@import "/vendor/bootstrap/less/utilities.less"; // Has to be last to override when necessary

// Theme Overrides

// Bootstrap default
// @import "/vendor/bootstrap-less-themes/themes/default/overrides.less";

// Sapling default
@import "/vendor/bootstrap-less-themes/themes/isapling/overrides.less";

```

## Copyright and license

Copyright 2013 Kyle Finley

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this work except in compliance with the License.
You may obtain a copy of the License in the LICENSE file, or at:

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
