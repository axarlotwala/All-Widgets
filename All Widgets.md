https://help.github.com/en/articles/basic-writing-and-formatting-syntax
https://help.github.com/en/github/writing-on-github/organizing-information-with-tables



# Flutter Documents Tools and Short Intro of Usages

    | Widgets Name | Widgets Usages |
    | --- | --- |
 
    | Materialapp | return Material Componant use material design librarary or componant |
    | home | is DeFault Show Which Screen You Want To Show First |
    | runapp() | in main Point Of App Provide Various Widget |
    | center | set Widget Into Main screen of Center |
    | widget | Full Flutter Framework  Depending in Widget and all about its Widget |
    scaffold    -   use for addd appbar,body,navigation,flotingActionBar,Bottom Navigation.
    StatelessWidget - Use For Static Item. like images & icon.
    StateFullWidget - use For dynamic Controll like Button Click.
    BuildContext/Build method    -  widget is inserted into the tree in a given BuildContext (Widget is Depending on Build Context)
    child       -   Child Set Only Single Widget Layout for example, Center or Container
    Children    - Children set Multipal Widgets for example, Row, Column, ListView, or Stack.
    renderObject    - 
    Text        -   Show TextView Into App
    Row,column  - Row set Horizonatl View and Column Set vertical View
    Stack       - These Widget Work as Stack Level Management , Relative Top,Right,bottom,left edge set  in stack.
    Positioned  - These Widget Depend On Stack and set Position Of Item.         
    Container   - For Creating rectangleBox or Drawable Custom View also add padding, margins, borders, or background color also use as child                  row and column
    BoxDecoration -  container use box decoration for border and shadow.
    shape       - Shape Class provide rectangle or circler shape.
    Expanded    - 
    Flex        - for Resize of View Somethig Like In Android Layout Weight.so flexibale way to manage views. 
    overlay     - Show Something Like Notificaton Bedges.
    Navigate    - Navigate From One Screen To Another New or Back.
         - route       - New Route for Navigation.
         - navigator.push  - for open new Screen.
         - navigator.pop   - for back to screen.
         - nameRoute - Use For Same In The Scrren and Navigate into other part in same Screen Like Bottom Navigation,Navigation Drawer,                       TabLayout.
         - send Data To New Screen -  only pass index for send Data To New Screen
         -  Return Data to Scrren  -   Provide Functionality For Retrun event Data.   
    OnTap      -  Click event For Items and list and widget.
    OnPress    - Same as clickEvent.
    state      - Holding The State.
    setstate   - Store the current state and which widget status you wan to change.
    dispose    - distroy the state
    keys       - 
    GlobalKeys - 
    mainAxisAlignment  - main axis runs horizontally 
    crossAxisAlignment -  cross axis runs vertically
    Image.network       - Fetch Image For internet.
    GridView   - For show in graid.
    ListView   - Infinite scrollable list.
    ListTile: Organizes up to 3 lines of text, and optional leading and trailing icons, into a row.
    form       - For Creating Form
    FormField  - for Update and Validation and manage Current state of Form.
    layoutBuilder - Build a Widget Tree for that can depended on parent widget.
    mediaQuery  - get the real-time size of the window,acsess Size of Screen.set for diffrence sceen size wise.
    transform   - for widget transform Animation.
    createState - createState creates the state class.a buildContext is assigned to that state.It is turns true when the buildContext is                       assigned.
    align        - to which side you want display item left,top,right,bottom.
    aspectRatio  - ratio between the height and width of widgets for more specific child.
    baseline     - set widget on base in line.
    center       - set Layout in center
    constraintBox - 
    customSingleChildLayout - 
    fittedBox     - set data in fit into the device size atomatic not scale down to item.
    fractionSizeBox  - 
    limitedBox    - fix height and width of  any widget.
    IntrinsicHeight - 
    IntrinsicWidth  - 
    wrap            - Same as android wrap containt but advance is which direction you want to wrap.
    sizebox         - providing Height and width of the widgets.
    futureBuilder   - 
    stremBuilder    - in event occure change ui and task async way...
    backdrop filter - for applying image filter rotation and blur.
    opacity - for hiding widget without remove space then use.
    drawer - drawaer class provide navigation drawer of material design.
    orientationBuilder  - provide query for screen size wise rotate mode & landscape mode show how mych data and how to view data example of                         graid view.
    Theme        - Theme data use for whole app theme set.
    tabs         - for showing tabs.
              
     # Dart Info usefull.

     dynamic   - they return any kind of  datatype.
     const     - cannot change value fix value.