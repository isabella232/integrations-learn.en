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
            <td>Experience Cloud applications</td>
            <td>Integrates using</td>
            <td>When to use</td>
            <td>Common use cases</td>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><a href="../../integrations/tutorials/analytics-cja/experience-platform-source-connector.md" target="_blank" rel="noreferrer">Analytics with Customer Journey Analytics</a></td>
            <td>Experience Platform source connector</td>
            <td>
                <ul>
                    <li>TODO: Use this integration to ingest Analytics data into Experience Platform from your report suites.</li>
                    <li>When data availability to the Customer Profile can be between 2-30 minutes from the time of data collection, and availability to the Data Lake is up to 90 minutes.</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li>Straightforward, user-interface initiated workflow.</li>
                    <li>Mapping user-interface to copy Analytics props and eVars to new XDM fields.</li>
                    <li>Fastest way to get value from the Real-Time Customer Profile and Customer Journey Analytics.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><a href="https://www.adobe.com/" target="_blank" rel="noreferrer">LINK TODO: Analytics with Customer Journey Analytics</a></td>
            <td>Experience Platform Edge</td>
            <td>
                <ul>
                    <li>When you wan to implement a long-term strategy. This sends data directly from a device to the Experience Platform using the AEP Web SDK, AEP Mobile SDK, or the Edge Network Server API.</li>
                    <li>When you are a new customer or existing customer, who need Analytics data availability to the Customer Profile to support same and next page personalization use cases.</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li>Provides the greatest level of control for data collected to use for supporting your use cases.</li>
                    <li>Client-side data is easily mapped to XDM fields.</li>
                    <li>Quickest data availability to the Real-Time Customer Profile.</li>
                </ul>
            </td>
        </tr>  
    </tbody>          
</table>
