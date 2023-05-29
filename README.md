# Milee-OpenSource
Repository for Milee's OpenSource components. Implementation Coming Soon.

# About

Milee is an innovative AI-based solution that aims to tackle the critical issue of climate change by empowering individuals to make informed decisions about their digital consumption.

The core concept of Milee is to provide users with transparent and customized information on the carbon footprint of the digital products and services they use or plan to use, such as online shopping platforms, cloud storage providers, and digital media streaming services. The solution will be delivered as a browser extension, easily accessible and free of charge to anyone. Milee will use machine learning to calculate a product’s carbon footprint by aggregating publicly available data and scientific benchmarks on the environmental impact of digital technologies. The carbon footprint users save by using Milee can be called "Mileeage" and collected in a gamified way.

Milee's approach is novel in its focus on individual empowerment, as it puts the power to make a difference in the hands of people, rather than relying solely on governmental or corporate actions. By providing users with easy-to-understand and actionable information, Milee encourages individuals to consider the environmental impact of their digital choices and make changes accordingly. Milee's approach is unique in that it leverages the power of AI and machine learning to personalize information for each user and make it more relatable to them.

Milee's solution can be applied in numerous real-world scenarios. For instance, users shopping on e-commerce platforms such as Amazon or Alibaba can see the carbon footprint of the products they are considering, and use this information to choose a more environmentally friendly option. Similarly, individuals using cloud storage services like Google Drive or Dropbox can compare the environmental impact of each service and choose the one that has a lower carbon footprint. Milee can also be useful for media consumers, such as those considering which streaming service to subscribe to, as they can compare the carbon footprint of each service and make an informed decision.

The societal challenge that Milee addresses is the lack of awareness among individuals about the carbon footprint of their digital consumption. Many people do not realize the environmental impact of their digital activities, and thus do not consider ways to minimize their carbon footprint. Milee provides a unique solution to this problem by making information about carbon footprint easily accessible and personalized, and by empowering individuals to make more informed decisions.

Milee's solution is aligned with the United Nations Sustainable Development Goals (SDGs) by promoting responsible consumption and production (SDG 12) and taking urgent action to combat climate change (SDG 13). By addressing these goals, Milee has the potential to create significant positive societal impact.


# Technical Implementation
Milee will leverage a variety of technologies to implement the proposed AI solution. The technology stack will include web development tools, cloud computing services, and machine learning frameworks.

The web development stack will be built using JavaScript, HTML, and CSS. The browser extension will be built using the browser's native extension APIs, such as WebExtensions for Mozilla Firefox, Google Chrome, and other browsers. The extension will use these APIs to interact with the browser and display the climate impact of the digital products and services that the user interacts with.

Cloud computing services such as AWS or Google Cloud will be used to host and process the data. The server-side logic of Milee will be implemented using Node.js, a JavaScript runtime environment. Node.js will be used to handle user authentication, data storage, and other server-side tasks.

For the machine learning aspect of the project, we will use Python and popular machine learning libraries such as TensorFlow or PyTorch. The machine learning algorithms will be trained on publicly available datasets, such as the Greenhouse Gas Protocol dataset or the Open Carbon Footprint dataset. These datasets contain information about the carbon emissions of various products and services.

Milee will use Natural Language Processing (NLP) techniques to analyze the textual content of the digital products and services that the user interacts with. This will involve building a text classification tranformer model that can identify the relevant carbon footprint information from the product description or the product's website, and tokenizing the information before storing it in an in-house database. The model will be trained on a corpus of product descriptions and carbon footprint information.

The estimated carbon footprint of each digital product or service will be computed using the ML algorithms trained on the relevant datasets. The result will be displayed to the user in a simple and easy-to-understand format. This will enable users to make informed decisions about the digital products and services they consume.

Overall, Milee will leverage a combination of web development, cloud computing, and machine learning technologies to provide users with a novel and effective solution to address the pressing societal challenge of reducing carbon emissions.
