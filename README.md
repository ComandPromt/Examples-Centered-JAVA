# Examples-Centered-JAVA

# Centrar JComboBox

![Preview](preview.png)

~~~java

	JComboBox comboBox = new JComboBox();
	
	DefaultListCellRenderer listRenderer = new DefaultListCellRenderer();
	
	listRenderer.setHorizontalAlignment(DefaultListCellRenderer.CENTER);
	
	combobox.setRenderer(listRenderer);
	
~~~

# Centrar frame

~~~java

	frame.setLocationRelativeTo(null);

~~~

# Centrar JTextPane

~~~java

	StyleContext context = new StyleContext();

	StyledDocument document = new DefaultStyledDocument(context);

	Style style = context.getStyle(StyleContext.DEFAULT_STYLE);

	StyleConstants.setAlignment(style, StyleConstants.ALIGN_CENTER);

	JTextPane text = new JTextPane(document);

~~~
