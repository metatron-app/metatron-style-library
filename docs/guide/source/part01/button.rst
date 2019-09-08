Button UIs
---------------------------------------------
Share how to use the Button UI.


1. Filled Basic Button (Medium)
=================================================
This is the default style button form.

Image
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

    .. figure:: /_static/img/part01/button01-1.png
       :align: center

Markup Code
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

    .. code-block:: html
       :linenos:

        <a href="javascript:" class="ddp-btn-solid">Solid</a>
        <a href="javascript:" class="ddp-btn-solid ddp-dark">Solid</a>
        <a href="javascript:" class="ddp-btn-solid ddp-disabled">Solid</a>


Design Guide
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

    .. figure:: /_static/img/part01/button01.png
       :align: center

2. Filled Basic Buttons (Large)
=================================================


Image
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. figure:: /_static/img/part01/button02-1.png
   :align: center

Markup Code
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

    .. code-block:: html
       :linenos:

        <a href="javascript:" class="ddp-btn-solid2">Solid</a>
        <a href="javascript:" class="ddp-btn-solid2 ddp-dark">Solid</a>
        <a href="javascript:" class="ddp-btn-solid2 ddp-disabled">Solid</a>


3. Icon Buttons (Medium)
=================================================
Usually used for Popup screens.

Image
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. figure:: /_static/img/part01/button03-1.png
   :align: center

Markup Code
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

    .. code-block:: html
       :linenos:

        <a href="#" class=" ddp-btn-pop"><em class="ddp-btn-reset"></em>btn pop</a>
        <a href="#" class=" ddp-btn-pop ddp-bg-black"><em class="ddp-icon-checked"></em>btn pop</a>
        <a href="#" class=" ddp-btn-pop ddp-bg-black"><em class="ddp-icon-add2"></em>btn pop</a>
        <a href="#" class=" ddp-btn-pop ddp-bg-black"><em class="ddp-icon-link-plus"></em>btn pop</a>


4. Icon Buttons (Large)
=================================================


Image
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. figure:: /_static/img/part01/button04-1.png
   :align: center

Markup Code
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

    .. code-block:: html
       :linenos:

        <a href="javascript:" class="ddp-btn-buttons2"><em class="ddp-icon-shot"></em>SNAPSHOT</a>
        <a href="javascript:" class="ddp-btn-buttons3">DONE</a>

Design Guide
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

    .. figure:: /_static/img/part01/button04.png
       :align: center



5. Toggle Buttons (List Buttons)
=================================================


Image
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. figure:: /_static/img/part01/button05-1.png
   :align: center

Markup Code
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

    .. code-block:: html
       :linenos:

        <ul class="ddp-list-buttons ddp-tab3">
            <li class="ddp-selected">
                All time
            </li>
            <li>
                Relative
            </li>
            <li class="">
                Specific
            </li>
        </ul>
        <ul class="ddp-list-buttons ddp-type2">
            <li class="ddp-selected">
                <em class="ddp-icon-check"></em>
                <label class="ddp-label-radio">
                    <input type="radio" checked="checked">
                    <i class="ddp-icon-radio"></i>
                    <span class="ddp-txt-radio">Single</span>
                </label>
            </li>
            <li class="">
                <em class="ddp-icon-check"></em>
                <label class="ddp-label-checkbox">
                    <input type="checkbox" checked="checked">
                    <i class="ddp-icon-checkbox"></i>
                    <span class="ddp-txt-checkbox">Multiple</span>
                </label>
            </li>
        </ul>
        <ul class="ddp-list-buttons ddp-type3 ">
            <li class="">
                Mo
            </li>
            <li class="">
                Tu
            </li>
            <li class="">
                We
            </li>
            <li class="ddp-selected">
                Th
            </li>
            <li class="">
                Fr
            </li>
            <li class="">
                Sa
            </li>
            <li class="">
                Su
            </li>
        </ul>
        <ul class="ddp-list-buttons ddp-dark">
            <li class="">
                개별 설정
            </li>
            <li class="ddp-selected">
                일괄 설정
            </li>
        </ul>
        <div class="ddp-list-tab-button ddp-type ddp-fleft">
            <!-- 선택시 ddp-selected 추가 -->
            <span class="ddp-selected"><em class="ddp-icon-tool-selectbox"></em></span>

            <span><em class="ddp-icon-tool-list"></em></span>
        </div>

Design Guide
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

    .. figure:: /_static/img/part01/button04.png
       :align: center


6. Checkbox Buttons
=================================================


Image
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. figure:: /_static/img/part01/button06-1.png
   :align: center

Markup Code
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

    .. code-block:: html
       :linenos:

        <label class="ddp-label-checkbox ddp-type">
            <input type="checkbox" checked="checked">
            <i class="ddp-icon-checkbox"></i>
            <span class="ddp-txt-checkbox">unchecked</span>
        </label>
        <label class="ddp-label-checkbox ddp-check-disabled">
            <input type="checkbox" checked="checked">
            <i class="ddp-icon-checkbox"></i>
            <span class="ddp-txt-checkbox">unchecked</span>
        </label>
        <label class="ddp-label-checkbox">
            <input type="checkbox">
            <i class="ddp-icon-checkbox"></i>
            <span class="ddp-txt-checkbox">unchecked</span>
        </label>
        <label class="ddp-label-checkbox">
            <input type="checkbox" checked="checked">
            <i class="ddp-icon-checkbox"></i>
            <span class="ddp-txt-checkbox">checked</span>
        </label>
        <label class="ddp-label-checkbox ddp-type2">
            <input type="checkbox" checked="checked">
            <i class="ddp-icon-checkbox"></i>
            <span class="ddp-txt-checkbox">unchecked</span>
        </label>
        <label class="ddp-label-checkbox ddp-type3">
            <input type="checkbox" checked="checked">
            <i class="ddp-icon-checkbox"></i>
            <span class="ddp-txt-checkbox">unchecked</span>
        </label>

Design Guide
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

    .. figure:: /_static/img/part01/button06.png
       :align: center



7. Radio Buttons
=================================================


Image
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. figure:: /_static/img/part01/button07-1.png
   :align: center

Markup Code
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

    .. code-block:: html
       :linenos:

        <label class="ddp-label-radio">
            <input type="radio">
            <i class="ddp-icon-radio"></i>
            <span class="ddp-txt-radio">unchecked</span>
        </label>
        <label class="ddp-label-radio">
            <input type="radio" checked="checked">
            <i class="ddp-icon-radio"></i>
            <span class="ddp-txt-radio">checked</span>
        </label>
        <label class="ddp-label-radio">
            <input type="radio" disabled="disabled">
            <i class="ddp-icon-radio"></i>
            <span class="ddp-txt-radio">disabled</span>
        </label>
        <label class="ddp-label-radio ddp-radiotype">
            <input type="radio">
            <i class="ddp-icon-radio"></i>
            <span class="ddp-txt-radio">patch</span>
        </label>

Design Guide
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

    .. figure:: /_static/img/part01/button07.png
       :align: center