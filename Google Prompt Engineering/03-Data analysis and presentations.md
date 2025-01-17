# AI for Professionals

Gen AI tools can help manage, analyze, visualize, and present data. These tools can help extract insights from data by identifying trends and patterns. To effectively use these tools, it's important to check if they can handle data and to follow your organization’s policies regarding sensitive information.

## Data Analysis and Visualizations

You can upload data from Google Drive or your computer. Gen AI can help with organizing data, calculating values, and understanding relationships between variables. For example, a gen AI tool can create a new column in a spreadsheet to calculate the average sales per customer.

These tools can also identify correlations in the data and suggest potential reasons behind trends, assisting with decision-making. For instance, a gen AI tool can analyze sales data to discover that smaller stores are outperforming larger ones, and then suggest reasons for this trend.

Gen AI tools can help with spreadsheet formulas by explaining them in step-by-step terms, and by troubleshooting error messages. With the help of gen AI tools, data analysis can be done with a few prompts, saving time.

Gen AI tools can recommend the best types of charts and graphs to visualize data. When prompting for visualizations, it is important to be clear about the type of chart and parameters needed. You can ask a gen AI tool for suggestions on what type of chart might work best. For example, you can prompt a model to describe a data set (such as a spreadsheet with columns for Title, Published, Genre, First Published and Approximate Sales in millions) to find out what kind of chart might work best for it.

You can ask a gen AI tool to generate different chart options based on a description of the data, as well as explanations about each chart. For example, you can ask for a chart that shows the correlation between genre and sales, then ask for an explanation of how they are correlated, and get several chart suggestions. You can also use a reference chart to get suggestions for creating a similar chart with your data.

- Upload a sample chart, then prompt the model to describe the chart.
- Ask the AI for recommendations on visualizing your data in the same way as the reference chart.
- The AI can provide instructions about how to create a new chart with your data, even explaining how to modify the chart.

## Create Presentations

Gen AI can organize presentations into compelling stories, build talking points, and create images to keep audiences engaged. You can prompt a gen AI tool to help figure out how to structure a presentation and summarize findings. For example, you can give the tool a persona, context, and then specify the task to structure the presentation and the desired format.

Gen AI can suggest a structure for your presentation, including key points and visuals for each slide. When generating images, you can be as descriptive as possible, specifying size, color, position, and overall aesthetic. Gen AI can generate various images that you can evaluate. Gen AI can also generate speaker notes. You can prompt it to provide multiple options for speaker notes, and then to adjust the speaker notes based on the audience.

## Gen AI Parameters

**Temperature:** This parameter controls the randomness of the gen AI output. A lower temperature favors more likely and expected results, which is recommended when accuracy is important, such as when summarizing an academic paper. A higher temperature gives less likely results a better chance of being selected, which can be useful for creative tasks.

**Top-k:** This value sets the total number of tokens from which the gen AI tool selects its output. A lower top-k value narrows the field of available options, reducing hallucinations. A higher top-k value can produce surprising results, useful when brainstorming. Setting the top-k value to 1 is the same as setting the temperature to 0 and guarantees the most likely result.

**Top-p:** This value further refines the pool of tokens by using total combined probability. A lower top-p value removes the least likely responses, which may work best when asking an AI tool to process statistics. A higher top-p value allows the AI tool to choose between responses more freely, which can help with tasks that require comparisons between outcomes. At the default setting of 1.0, the top-p value has no effect on sampling.
