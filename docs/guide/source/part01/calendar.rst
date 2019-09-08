Calendar & Time
---------------------------------------------
Share how to use the Calendar UI.


1. Basic Time
=================================================

Image
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

    .. figure:: /_static/img/part01/calendar01-1.png
       :align: center

Markup Code
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

    .. code-block:: html
       :linenos:

        <div class="ddp-wrap-edit ddp-clear">
            <label class="ddp-label-type">Time</label>

            <div class="ddp-ui-edit-option">

                <a href="#" class="ddp-btn-toggle ddp-all ddp-selected">All</a>
                <a href="#" class="ddp-btn-toggle ddp-today">Today</a>
                <a href="#" class="ddp-btn-toggle ddp-last">Last 7 days</a>

                <div class="ddp-ui-calen ddp-clear" style="width:320px;">
                    <div class="ddp-box-calen ">
                        <input type="text" id="calen1" class="ddp-input-typebasic ddp-data-calen ddp-top" value="2017-30-30">
                    </div>

                    <span class="ddp-bar">~</span>
                    <div class="ddp-box-calen">
                        <input type="text" id="calen4 " class="ddp-input-typebasic ddp-data-calen " value="2017-30-30">
                    </div>
                </div>
                <a href="#" class="ddp-btn-line-s">적용</a>
            </div>
            <!-- //edit option -->
        </div>

2. Selected Date & Time Picker (Inline)
=================================================

Image
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

    .. figure:: /_static/img/part01/calendar02-1.png
       :align: center

Markup Code
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

    .. code-block:: html
       :linenos:

       <div class="ddp-form-date ddp-inline">
           <!-- day -->
           <div class="ddp-day">
               <span class="ddp-label-date">From</span>
               <div class="ddp-box-date ddp-focus ddp-edit">
                   <em class="ddp-icon-apply"></em>
                   <div class="ddp-wrap-input">
                       <em class="ddp-icon-calen"></em>
                       <input type="text" value="2018-01-01 13:13">
                   </div>
               </div>
           </div>
           <!-- //day -->
           <!-- day -->
           <div class="ddp-day">
               <span class="ddp-label-date">To</span>
               <div class="ddp-box-date">
                   <em class="ddp-icon-apply"></em>
                   <div class="ddp-wrap-input">
                       <em class="ddp-icon-calen"></em>
                       <input type="text" value="2018-01-01 13:13">
                   </div>
               </div>
           </div>
           <!-- //day -->
        </div>


3. Selected Date & Time Picker
=================================================

Image
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

    .. figure:: /_static/img/part01/calendar02-1.png
       :align: center

Markup Code
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

    .. code-block:: html
       :linenos:

        <div class="ddp-form-date ">
                <!-- day -->
                <div class="ddp-day">
                    <span class="ddp-label-date">From</span>
                    <div class="ddp-box-date ddp-focus ddp-edit">
                        <em class="ddp-icon-apply"></em>
                        <div class="ddp-wrap-input">
                            <em class="ddp-icon-calen"></em>

                            <input type="text" value="2018-01-01 13:13">
                        </div>
                    </div>
                </div>
                <!-- //day -->
                <!-- day -->
                <div class="ddp-day">
                    <span class="ddp-label-date">To</span>
                    <div class="ddp-box-date">
                        <em class="ddp-icon-apply"></em>
                        <div class="ddp-wrap-input">
                            <em class="ddp-icon-calen"></em>

                            <input type="text" value="2018-01-01 13:13">
                        </div>
                    </div>
                </div>
                <!-- //day -->
            </div>