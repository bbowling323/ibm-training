@app.callback(
    Output(component_id='plot1', component_property='children'),
    Output(component_id='plot2', component_property='children'),
    Output(component_id='plot3', component_property='children'),
    Output(component_id='plot4', component_property='children'),
    Output(component_id='plot5', component_property='children')
],
        Input(component_id='input-type', component_property='value'),
        Input(component_id='input-year', component_property='value')],
        
