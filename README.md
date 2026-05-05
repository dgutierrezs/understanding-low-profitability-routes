# Understanding low profitability routes

Análisis desarrollado como parte de mi transición hacia data science, aplicando Python y pandas a problemas reales de logística y optimización de rutas.

La base de datos para este repositorio también esta obtenida por Kaggle. Esta vez, he utilizado Python.

Root Cause Analysis: Why Are Some Routes Underperforming?
Business Context
In the previous analysis, several routes were identified as consistently unprofitable, with a high percentage of trips generating losses. While this highlights where value is being lost, it does not explain why these routes are underperforming.

Understanding the drivers behind poor performance is critical for making effective decisions. Without identifying the root causes, actions such as eliminating or optimizing routes may not address the underlying issues.

Objective
The objective of this analysis is to investigate whether operational inefficiencies contribute to route underperformance.

Specifically, we aim to determine if unprofitable routes differ from high-performing ones in terms of fuel efficiency and operational time.

Approach
To achieve this, routes will be grouped based on their performance category (high-performing vs unprofitable), and key operational metrics will be compared across groups.

The analysis will focus on:

Fuel efficiency (fuel consumption per distance, average MPG)
Trip duration and idle time
By comparing these metrics, we aim to identify whether inefficiencies in operations help explain the differences in profitability across routes.
