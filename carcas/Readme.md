[Руководство по стилю.docx](https://github.com/Banstra/exam/files/12812695/default.docx)

Стили:
[ ] установка логотипов: не забывать про свойство resource
![image](https://github.com/Banstra/exam/assets/97594123/634067d7-5c41-41e0-ad8b-06c8e378c04b)

[ ] не искажать логотип
[ ] для приложения должна быть иконка ![image](https://github.com/Banstra/exam/assets/97594123/889e4570-cb03-43f4-a917-7984066c49ab)

[ ] шрифт
структура APP.xaml:
1. через <style target type = тег объекта>
2. <setter свойства и значения свойства>

    <Style TargetType="TextBlock">
            <Setter Property="FontFamily" Value="Tw Cen TM"></Setter>
            
        </Style>
        <Style TargetType="TextBox">
            <Setter Property="FontFamily" Value="Tw Cen TM"></Setter>

        </Style>
        <Style TargetType="Button">
            <Setter Property="FontFamily" Value="Tw Cen TM"></Setter>

        </Style>

   [ ] цветовая схема
![image](https://github.com/Banstra/exam/assets/97594123/42368160-a4c2-4d78-af07-f6143544d570)
![image](https://github.com/Banstra/exam/assets/97594123/2894f05e-f3f7-4df7-b4cc-2e3c05827de2)
![image](https://github.com/Banstra/exam/assets/97594123/6ebfc9bc-5466-4ae1-8c0c-81500a75dcab)
Дополнительно:
цвета можно указать через <SolidColorBrush x:key="название" Color="значение"></SolidColorBrush>
 <Grid Background="LightGray" или Background="{StaticResource LightGray}">
 
