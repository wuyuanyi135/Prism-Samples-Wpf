IsNavigationTarget is used to determine whether this view need to be recreated.
the tab header is in
    <UserControl.Resources>
        <Style TargetType="TabItem">
            <Setter Property="Header" Value="{Binding DataContext.SelectedPerson.FirstName}" />
        </Style>
    </UserControl.Resources>
