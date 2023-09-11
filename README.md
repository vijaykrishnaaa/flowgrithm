# flowgrithm

<?xml version="1.0"?>
<flowgorithm fileversion="3.0">
    <attributes>
        <attribute name="name" value=""/>
        <attribute name="authors" value="Vijay"/>
        <attribute name="about" value=""/>
        <attribute name="saved" value="2023-09-11 02:58:04 PM"/>
        <attribute name="created" value="VmlqYXk7VklKQVktTEFQVE9QOzIwMjMtMDktMTE7MDI6NDc6NTYgUE07MjY5Nw=="/>
        <attribute name="edited" value="VmlqYXk7VklKQVktTEFQVE9QOzIwMjMtMDktMTE7MDI6NTg6MDQgUE07MTsyODAw"/>
    </attributes>
    <function name="Main" type="None" variable="">
        <parameters/>
        <body>
            <declare name="radius" type="Integer" array="False" size=""/>
            <declare name="area" type="Real" array="False" size=""/>
            <declare name="circumference" type="Real" array="False" size=""/>
            <output expression="&quot;enter radius&quot;" newline="True"/>
            <input variable="radius"/>
            <assign variable="area" expression="3.14*(radius)^2"/>
            <assign variable="circumference" expression="2*3.14*radius"/>
            <output expression="area" newline="True"/>
            <output expression="circumference" newline="True"/>
        </body>
    </function>
</flowgorithm>
