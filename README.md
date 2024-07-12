# pymaecuticals-Inc.-challenge
Pymaceuticals,Inc. challenge
##### Changes or corrections made with XpertLearning Assistant
###### 1. On this line of code plt.bar(x_axis, total_drug_tpoints, color = '#0072B2', alpha=1, align="edge", width=0.6) the code snipet "color = '#0072B2', alpha=1,"
###### 2. On this line of code plt.pie(data_pie, labels=labels, autopct='%1.1f%%', startangle=90) this code snipet "autopct='%1.1f%%', startangle=90)"
###### 3. On this line of code final_volume = clean_merge_study_metadata[(clean_merge_study_metadata['Timepoint'] == 45) & 
###### (clean_merge_study_metadata['Drug Regimen'].isin(['Capomulin', 'Ramicane', 'Infubinol', 'Ceftamin']))].groupby('Mouse ID')['Timepoint'].max() this addition of the isin() function
###### 4. On this line of code  final_volume_data = merge_final_volume.loc[merge_final_volume.index.isin(merge_final_volume.groupby('Mouse ID')
###### ['Timepoint_x'].idxmax()),'Tumor Volume (mm3)'] the addition of the index() and isin() function as well as a change from max () function to idmax() function
###### 5. On this line of code outliers = final_volume_data[(final_volume_data<lower_bound)| (final_volume_data>upper_bound)] the use of the bitwise operator instead of the or operator
###### 6. On this line of code plt.boxplot(tumor_volume_data, labels=treatment_names, flierprops=dict(marker='o', markerfacecolor='r', markersize=8,
###### linestyle='none')) the code snipet "flierprops=dict(marker='o', markerfacecolor='r', markersize=8, linestyle='none'))
###### 7. On this line of code first_capomulin_value = regimen_capomulin.iloc[1, regimen_capomulin.columns.get_loc('Mouse ID')] the use of columns.get.loc
###### 8. On this line of code plt.plot(line_plot_data['Timepoint'], line_plot_data['Tumor Volume (mm3)'], marker='o', color='b', label='Mouse ID: ' + 
###### first_capomulin_value) the code snipet  marker='o',
