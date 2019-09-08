Selectbox
---------------------------------------------
Share how to use the Selectbox UI.


1. Icon Selectbox
=================================================

Image
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

    .. figure:: /_static/img/part01/selectbox01-1.png
       :align: center

Markup Code
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

    .. code-block:: html
       :linenos:

       <div>
           <!-- SELECTBOX -->
           <div class="ddp-type-selectbox ddp-selected">
               <span class="ddp-txt-selectbox">
                 <span class="ddp-icons">
                       <em class="ddp-icon-dimension-point ddp-icon-map-view"></em>
                   </span>
                   Color by Dimension
               </span>
               <div class="ddp-wrap-popup2 ">
                   <ul class="ddp-list-popup">
                       <li>
                           <a href="#">
                               Series
                           </a>
                       </li>
                       <li>
                           <a href="#">
                               Series
                           </a>
                       </li>
                       <li>
                           <a href="#">
                               SeriesSeriesSeries
                           </a>
                       </li>
                       <li>
                           <a href="#">
                               Series
                           </a>
                       </li>
                   </ul>
               </div>
           </div>
           <!-- //SELECTBOX -->
           </div>

2. Icon Selectbox (Selected)
=================================================

Image
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

   .. figure:: /_static/img/part01/selectbox02-1.png
      :align: center

Markup Code
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

   .. code-block:: html
      :linenos:

        <div style="height:150px">
            <!-- hover selectbox -->
            <div class="ddp-hover-selectbox ddp-selected ">
                <a href="javascript:" class="ddp-icon-type"> <em class="ddp-icon-type-ab"></em> Time / Date</a>
                <!-- popup -->
                <div class="ddp-wrap-popup2 ddp-types">
                    <ul class="ddp-list-popup">
                        <li class="ddp-selected">
                            <a href="#">
                                <em class="ddp-icon-type-ab"></em>
                                Text
                                <em class="ddp-icon-check"></em>
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                <em class="ddp-icon-type-tf"></em>
                                Boolean
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                <em class="ddp-icon-type-int"></em>
                                Integer
                            </a>
                        </li>
                    </ul>
                </div>
                <!-- //popup -->
            </div>
            <!-- //hover selectbox -->
        </div>

3. Selected Selectbox
=================================================

Image
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

   .. figure:: /_static/img/part01/selectbox03-1.png
      :align: center

Markup Code
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

   .. code-block:: html
      :linenos:

        <div class="ddp-type-dropdown ddp-selected">
            <a href="javascript:" class="ddp-data-sort">Name ascending
                <em class="ddp-icon-array-default2"></em>
                <em class="ddp-icon-array-asc2" style="display:none;"></em>
                <em class="ddp-icon-array-des2" style="display:none;"></em>
            </a>
            <!-- popup -->
            <div class="ddp-wrap-popup2">
                <ul class="ddp-list-popup">
                    <li class="ddp-selected">
                        <a href="#">
                            Name ascending
                            <em class="ddp-icon-check"></em>
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            Name descending
                            <em class="ddp-icon-check"></em>
                        </a>
                    </li>
                </ul>
            </div>
            <!-- //popup -->
        </div>


4. Checked Selectbox
=================================================

Image
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

   .. figure:: /_static/img/part01/selectbox04-1.png
      :align: center

Markup Code
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

   .. code-block:: html
      :linenos:

        <div class="ddp-wrap-popup2 ">
            <span class="ddp-txt-label2">
                Filter
            </span>
            <ul class="ddp-list-popup">

                <li class="">
                    <a href="javascript:">
                        <label class="ddp-label-checkbox">
                            <input type="checkbox">
                            <i class="ddp-icon-checkbox"></i>
                            <span class="ddp-txt-checkbox">unchecked</span>
                        </label>
                    </a>
                </li>
                <li class="">
                    <a href="javascript:">
                        <label class="ddp-label-checkbox">
                            <input type="checkbox">
                            <i class="ddp-icon-checkbox"></i>
                            <span class="ddp-txt-checkbox">unchecked</span>
                        </label>
                    </a>
                </li>
                <li class="">
                    <a href="javascript:">
                        <label class="ddp-label-checkbox">
                            <input type="checkbox">
                            <i class="ddp-icon-checkbox"></i>
                            <span class="ddp-txt-checkbox">unchecked</span>
                        </label>
                    </a>
                </li>
            </ul>
        </div>