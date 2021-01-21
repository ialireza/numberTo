# numberTo
Convert numbers to other languages in datatables

تبدیل اعداد به زبان فارسی, انگلیسی و عربی در دیتاتیبل

**example**

    $('#example').DataTable( {
       columnDefs: [
         {
               data: 'id',
               name: 'id',
               fnCreatedCell: function (nTd, sData, oData, iRow, iCol) {
                   $(nTd).html($.fn.dataTable.numberTo(oData.id, 'fa'));
               }
         },
       ]
    } );
****
پیش‌فرض زبان تبدیل **فارسی** در نظر گرفته شده است.

**CDN**

