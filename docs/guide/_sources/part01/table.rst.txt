Table
---------------------------------------------
Share how to use the Table UI.


1. Basic Table
=================================================
The default Table UI is often used in initial list screens and popups. The class name used is 'ddp-table-form'.

Image
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

    .. figure:: /_static/img/part01/table01-1.png
       :align: center

Markup Code
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

    .. code-block:: html
       :linenos:

        <table class="ddp-table-form ddp-table-type2">
            <colgroup>
                <col width="51px">
                <col width="*">
                <col width="10%">
                <col width="15%">
                <col width="15%">
            </colgroup>
            <thead>
            <tr>
                <th class="ddp-txt-center">
                    No.

                </th>
                <th>
                    Data
                    <em class="ddp-icon-array-default2"></em>
                    <em class="ddp-icon-array-asc2" style="display:none;"></em>
                    <em class="ddp-icon-array-des2" style="display:none;"></em>
                    <!-- hover info -->
                    <div class="ddp-wrap-hover-info">
                        <em class="ddp-icon-info3 "></em>

                        <!-- popup -->
                        <div class="ddp-box-layout4 ">
                            <div class="ddp-data-title">
                                What is Ingestion tunning
                                configuration?
                            </div>
                            <div class="ddp-data-det">
                                Ingestion tunning configuration describes effective options when ingestion.Now put it in the corresponding text box in JSON format. Here is an example:<br><br>
                                “maxRowsInMemory” : 75000,<br>
                                “maxOccupationInMemory” : -1,<br>
                                “maxShardLength” : -2147483648,  <br>   “leaveIntermediate” : false,<br>
                                “cleanupOnFailure” : true,<br>
                                “overwriteFiles” : false,<br>
                                “ignoreInvalidRows” : false,<br>
                                “assumeTimeSorted” : false
                            </div>
                        </div>
                        <!-- //popup -->
                    </div>
                    <!-- //hover info -->
                </th>
                <th>
                    Type
                </th>
                <th>
                    Used in
                    <em class="ddp-icon-array-default2"></em>
                    <em class="ddp-icon-array-asc2" style="display:none;"></em>
                    <em class="ddp-icon-array-des2" style="display:none;"></em>
                </th>
                <th>
                    Updated
                    <em class="ddp-icon-array-default2"></em>
                    <em class="ddp-icon-array-asc2" style="display:none;"></em>
                    <em class="ddp-icon-array-des2" style="display:none;"></em>
                </th>
            </tr>
            </thead>

        </table>


2. Basic Table2
=================================================

Image
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

    .. figure:: /_static/img/part01/table02-1.png
       :align: center

Markup Code
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

    .. code-block:: html
       :linenos:

        <table class="ddp-table-form2">
            <colgroup>
                <col width="*">
                <col width="28%">
                <col width="20%">
                <col width="30px">
            </colgroup>
            <thead>
            <tr>
                <th>
                    ID
                </th>
                <th>
                    UserName
                </th>
                <th>
                    Role
                </th>
                <th class="ddp-table-icons">

                </th>
            </tr>
            </thead>

        </table>

3. Single Detail Table
=================================================

Image
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

    .. figure:: /_static/img/part01/table03-1.png
       :align: center

Markup Code
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

    .. code-block:: html
       :linenos:

        <table class="ddp-table-detail">
            <colgroup>
                <col width="160px">
                <col width="*">
            </colgroup>
            <tbody>
            <tr>
                <th>
                    Name
                </th>
                <td>
                    John Smith
                </td>
            </tr>
            <tr>
                <th>
                    ID
                </th>
                <td>
                    smith001
                </td>
            </tr>
            <tr>
                <th>
                    Email
                </th>
                <td>
                    <a href="javascript:" class="ddp-link-window">Smith001@email.com</a>
                </td>
            </tr>
            <tr>
                <th>
                    Permission
                </th>
                <td>
                    Grants access to personal workspace, Shared workspace, Data management &amp; System setting 길어지면 개행 Grants access to personal workspace, Shared workspace,
                    Data management &amp; System setting 길어지면 개행

                </td>
            </tr><tr>
                <th>
                    Phone
                </th>
                <td>
                    <span class="ddp-data-none">None</span>

                </td>
            </tr>
            </tbody>
        </table>