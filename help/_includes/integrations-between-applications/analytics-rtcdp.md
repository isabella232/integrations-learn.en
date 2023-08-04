---
---

# Integrate Adobe Analytics with Real-Time Customer Data Platform 

{{analytics-description}}

{{real-time-cdp-description}}

Integrating Adobe Analytics with Adobe Real-Time Customer Data Platform (Real-Time CDP) can offer several benefits for businesses looking to enhance their customer experiences and marketing efforts. Here are some of the key advantages:

+ **Enhanced audience targeting & personalization**: Precise marketing on devices & channels, tailored messages for optimized engagement.
+ **Improved landing page optimization**: Tailored experiences based on device & behavior, enhancing user satisfaction & conversion.
+ **Seamless audience activation**: Utilize customer profiles for effective targeting through preferred channels, delivering relevant messages.

By combining Adobe Analytics and Real-Time CDP, businesses can take their marketing efforts to the next level, delivering personalized experiences, increasing customer engagement, and optimizing conversions across various digital touchpoints.

<table>
    <thead>
        <tr>
            <th>Experience Cloud applications</th>
            <th>Integrates using</th>
            <th>When to use</th>
            <th>Common use cases</th>
        </tr>
    </thead>
    <tr>
        <td rowspan="2">Analytics with Real-Time CDP</td>
        <td><a href="../../integrations/tutorials/analytics-rtcdp/experience-platform-source-connector.md" target="_blank" rel="noreferrer">Experience Platform source connector</a></td>
        <td>
            <ul style="margin-top: 0;">
                <li>Recommended approach for customers who have already implemented Adobe Analytics, and want the fastest way to ingest this data into Experience Platform to use in the Real-Time Customer Profile.</li>
                <li>When data availability to the Real-Time Customer Profile can be between 2-30 minutes from the time of data collection, and availability to the Data Lake is up to 90 minutes.</li>
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
       <td><a href="../../integrations/tutorials/analytics-rtcdp/experience-platform-edge.md" target="_blank" rel="noreferrer">Experience Platform Edge</a></td>
        <td>
            <ul style="margin-top: 0;">
                <li>Recommended approach for new Analytics implementations or when you want to implement a long-term strategy.</li>
                <li>Sends data directly from a device to the Experience Platform using the AEP Web SDK, AEP Mobile SDK, or the Edge Network Server API.</li>
                <li>New or existing customers who need Analytics data availability to the Real-Time Customer Profile to support same and next page personalization use cases.</li>
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
</table>
