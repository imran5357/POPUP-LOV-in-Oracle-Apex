# POPUP-LOV-in-Oracle-Apex

<pre>
COLUMN_NAME1:P1_ITEM_NAME1,COLUMN_NAME2:P1_ITEM_NAME2
</pre>
<pre>
  // Javascript Codes
  function(options) {
      var size_name, price, columns = options.columns;

      // set a minimum width for the dialog
      options.minWidth = 500;

      // PRICE
      price = columns.PRICE;
      price.width = 80;
      price.alignment = "right";
      price.noStretch = true;

      // Size Name
      size_name = columns.SIZE_NAME;
      size_name.width = 100;
      size_name.alignment = "left";
      size_name.noStretch = true;
      return options;
  }
</pre>
