---
permalink: /current-research/
title: "Current Research"
---

![DataDrivenModels](/assets/images/AI4NWP_Dalle3.jpeg) 

My current research centers on using machine learning for various meteorology tasks. 

**TL;DR:** I use the latest machine learning techniques to enhance satellite, radar and weather forecast tools. 

<h2> Tomorrow.io </h2>

Tomorrow.io is a startup company that provides value across the weather enterprise. Tomorrow.io has their own space program with currently 7 microwave sounders on orbit collecting data daily, with plans to extend this constellation to 12-14 to enable rapid revisits of microwave data everywhere on the globe. They also conduct their own AI weather forecasts, tuning the forecast for customer needs. Lastly, they serve these data on an automated platform and API that allow customers to automate processes based on their own needs and risks. My role at the company is to provide my microwave satellite and AI weather forecasting expertise to enhance internal research efforts that use both our microwave observations and weather forecasts. 

<h2> ICgen </h2>

With unprecedented microwave sounder information, the community has the opportunity to do hourly updating global weather forecasts. Unfortunatley, traditional NWP compute demands will not enable such rapidly updating forecasts. Thus, we have been exploring AI/ML methods in Data Assimaltion to create an inital weather state that then can be forecasted forward using AI-NWP like Aurora or FourCastNet. 

One of these methods is called Score-Based Data Assimlation (Rozet and Loupee 2023). This cleverly designed diffusion model, can be trained without any satellite data (i.e., just on ERA5) and then at inference time it can use observations to <i> guide </i> the diffusion model to closely match the observations. 