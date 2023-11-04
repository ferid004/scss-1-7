# scss 1-7 git bash code 
## dangers! pay attention to which terminal it is, it should be "GIT BASH".
## just copy it by clicking the link below  :arrow_heading_down:  and click right in the terminal

#### mkdir scss
mkdir scss/base
touch scss/base/_reset.scss
touch scss/base/_typography.scss
mkdir scss/components
touch scss/components/_buttons.scss
touch scss/components/_carousel.scss
touch scss/components/_cover.scss
touch scss/components/_dropdown.scss
mkdir scss/layout
touch scss/layout/_navigation.scss
touch scss/layout/_grid.scss
touch scss/layout/_header.scss
touch scss/layout/_sidebar.scss
touch scss/layout/_forms.scss
mkdir scss/pages
touch scss/pages/_home.scss
touch scss/pages/_contact.scss
mkdir scss/themes
touch scss/themes/_theme.scss
touch scss/themes/_admin.scss
mkdir scss/utils
touch scss/utils/_variables.scss
touch scss/utils/_functions.scss
touch scss/utils/_mixins.scss
touch scss/utils/_helpers.scss
mkdir scss/vendors
touch scss/vendors/_bootstrap.scss
touch scss/vendors/_jquery-ui.scss
echo "@import'./base/reset';
@import'./base/typography';
@import'./components/buttons';
@import'./components/carousel';
@import'./components/cover';
@import'./components/dropdown';
@import'./layout/forms';
@import'./layout/grid';
@import'./layout/header';
@import'./layout/navigation';
@import'./layout/sidebar';
@import'./pages/contact';
@import'./pages/home';
@import'./themes/admin';
@import'./themes/theme';
@import'./utils/functions';
@import'./utils/helpers';
@import'./utils/mixins';
@import'./utils/variables';
@import'./vendors/bootstrap';
@import'./vendors/jquery-ui';" > scss/main.scss
