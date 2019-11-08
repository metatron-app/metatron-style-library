Structure
---------------------------------------------
The purpose of this document is to present common development standards that screen developers need when developing mobile web screen UI, and to develop high quality screens that comply with standards in a short time.
All the items presented in this document are the rules that must be applied when developing the screen. If the standard is difficult to apply, it should be decided by consulting with the UI designer.


1. Basic Structure
=================================================
The location of the UI resource is located under the 'discovery-frontend > src > assets'.

    .. figure:: /_static/img/part00/structure.png
       :align: center


2. Basic CSS
=================================================
The location of the UI resource is located under the 'discovery-frontend > src > assets > css'.

    .. figure:: /_static/img/part00/css.png
       :align: center

We have two css folders. Under the 'lib' folder, css resources used by external libraries are located, and metas own css are under 'metatron' folder.

polaris.v2.css
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
It is a root css file.

polaris.c2.layout.css
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
This file defines layouts, margins, and padding. We are basically using 12 grids like Bootstrap. However, keep in mind that many UI components can throw exceptions.

    .. code-block:: css
       :linenos:

        .ddp-col-12 {width:100%;}
        .ddp-col-11 {width:91.66666667% !important;}
        .ddp-col-10 {width:83.33333333% !important;}
        .ddp-col-9 {width:75% !important;}
        .ddp-col-8  {width:66.66666667% !important;}
        .ddp-col-7 {width:58.33333333% !important;}
        .ddp-col-6 {width:50% !important;}
        .ddp-col-5 {width:41.66666667% !important;}
        .ddp-col-4 {width:33.33333333% !important;}
        .ddp-col-3 {width:25% !important;}
        .ddp-col-2 {width:16.66666667% !important;}
        .ddp-col-1 {width:8.33333333% !important;}

polaris.c2.component.css
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
This file defines the UI components that are common to all metatron tools. UI components such as login are defined.

polaris.c2.page.css
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
This file defines the commonly used page units (a set of UI components) in all metatron tools.

polaris.metatron.componet.css (under 'metatron' folder)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
This file defines metatron Discovery's common UI components.

    .. code-block:: css
       :linenos:

        @import url('component/component.icons.css'); /* ListFiltering */
        @import url('component/component.loading.css'); /* Loading */
        @import url('component/component.checkbox.css'); /* Checkbox */
        @import url('component/component.radio.css'); /* Radio */
        @import url('component/component.page.css'); /* Page */
        @import url('component/component.tooltip.css'); /* Tooltip */
        @import url('component/component.input.css'); /* Input */
        @import url('component/component.selectbox.css'); /* Selectbox */
        @import url('component/component.calen.css'); /* Calen */
        @import url('component/component.button.css'); /* Button */
        @import url('component/component.search.css'); /* Search */
        @import url('component/component.table.css'); /* Table */
        @import url('component/component.tag.css'); /* Tag */
        @import url('component/component.form.css'); /* Table */
        @import url('component/component.filtering.list.css'); /* ListFiltering */

polaris.metatron.page.css (under 'metatron' folder)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
This file defines a css with a high dependency on the page.

    .. figure:: /_static/img/part00/privatecss.png
       :align: center

3. Make Your Own CSS
=================================================
If you want to make your own new css, please register your file at the bottom of 'polaris.metatron.page.css' file.

    .. figure:: /_static/img/part00/privatecss2.png
       :align: center

