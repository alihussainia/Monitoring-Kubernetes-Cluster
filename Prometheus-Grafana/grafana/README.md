# Grafana Dashboard

1. Visit http://[NODEIP]:32000 to view the Grafana dashboard.
2. Login with `admin` and `admin` for the username and password. You can reset the password on the next screen or click `Skip`.
3. On the `Welcome to Grafana` page click on the `+` sidebar icon in the upper-left corner of the screen.
4. Click the drop-down item named `imports` from the available options. 
5. Enter an ID value of `10000` into the `Grafana.com Dashboard` textbox and click `Load`. This will load the `Cluster Monitoring for Kubernetes` dashboard.

**Note:** 
You can find a list of pre-configured dashboards at https://grafana.com/grafana/dashboards. Each one will have an id you can copy into the Grafana `Import dashboard` screen.

7. On the next screen you'll see a `Select a Prometheus data source` drop-down. Select `prometheus` from the list and click `Import`. Your dashboard will now load.
8. Click on the `Cluster Monitoring for Kubernetes` drop-down in the uppper-left corner of the screen. Go back through the steps to import a dashboard but this time enter an ID of `8588`. This will load the `Kubernetes Deployment Statefulset Daemonset metrics` dashboard.
9. If you click on the dashboard name drop-down in the upper-left corner of the screen you'll see both of your dashboards listed and can now switch between them.
10. Import the dashboard with an ID of `10694`. This dashboard is called `Container Statistics`. 
11. From here you can load other dashboards or create your own!

