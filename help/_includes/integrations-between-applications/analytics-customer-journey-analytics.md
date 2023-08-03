---
---

# Integrate Adobe Analytics with Customer Journey Analytics

{{analytics-description}}

{{customer-journey-analytics-description}}

Integrating Adobe Analytics with Customer Journey Analytics offers key benefits:

+ **Comprehensive insights** into customer behaviors and preferences.
+ **Seamless cross-channel tracking** for a holistic view.
+ **Unified data and reporting** for accurate analysis.
+ **Enhanced personalization** and improved customer engagement.
+ **Real-time data insights** for agile decision-making.

## Common integrations

<table>
    <thead>
        <tr>
            <th>Experience Cloud applications</th>
            <th>Integrates using</th>
            <th>When to use</th>
            <th>Common use cases</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan="2">Analytics and Customer Journey Analytics</td>
            <td><a href="../../integrations/tutorials/analytics-cja/experience-platform-source-connector.md" target="_blank" rel="noreferrer">Experience Platform source connector</a></td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Recommended approach for customers who have already implemented Adobe Analytics, and want the fastest way to ingest this data into Experience Platform to use in Customer Journey Analytics.</li>
                    <li>When data availability to the Customer Profile can be between 2-30 minutes from the time of data collection, and availability to the Data Lake is up to 90 minutes.</li>
                </ul>
            </td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Straightforward, user-interface initiated workflow.</li>
                    <li>Mapping user-interface to copy Analytics props and eVars to new XDM fields.</li>
                    <li>Fastest way to get value from the Real-Time Customer Profile and Customer Journey Analytics.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><a href="../../integrations/tutorials/analytics-cja/experience-platform-edge.md" target="_blank" rel="noreferrer">Experience Platform Edge</a></td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Recommended approach for new Analytics implementations or when you want to implement a long-term strategy.</li>
                    <li>Sends data directly from a device to the Experience Platform using the AEP Web SDK, AEP Mobile SDK, or the Edge Network Server API.</li>
                </ul>
            </td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Provides the greatest level of control for data collected to use for supporting your use cases.</li>
                    <li>Client-side data is easily mapped to XDM fields.</li>
                    <li>Quickest data availability to the Real-Time Customer Profile.</li>
                </ul>
            </td>
        </tr>  
    </tbody>          
</table>
