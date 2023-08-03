---
---

# Analytics and Audience Manager integration

{{analytics-description}}

{{audience-manager-description}}

Enabling this integration, by forwarding Adobe Analytics data server-side to Audience Manager, gives Audience Manager one of its major sources of data, namely online customer behavioral data. This data can then be combined with other data, like first-party CRM data or third-party partner data, to create rich customer segments. In addition, Audience Manager segments are then sent back to the webpage in the response for further visitor analysis. Both of these valuable use cases are described below.

The key benefits of integrating Adobe Analytics and Audience Manager are:

+ **Enhanced segmentation**: Combine Adobe Analytics & Audience Manager data for precise, personalized audience segments in marketing campaigns.
+ **Unified customer profiles**: Integrate data sources to understand interactions and behaviors, creating comprehensive customer profiles.
+ **Improved ad effectiveness**: Optimize ads with data-driven targeting from Adobe Analytics & Audience Manager integration.
+ **Data-driven decisions**: Inform choices through detailed insights, merging Adobe Analytics & Audience Manager data.
+ **Personalized experiences**: Tailor your content & offers, enriching customer interactions across touch-points using both platforms.

Overall, this integration brings together valuable data and audience insights. It enables businesses to create more targeted and relevant marketing campaigns while gaining a deeper understanding of their customers' preferences and behaviors.

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
            <td>
                <a href="/docs/analytics-learn/tutorials/integrations/audience-manager/enable-server-side-forwarding-in-adobe-launch.html" target="_blank" rel="noreferrer">Analytics sending data to Audience Manager</a>
            </td>
            <td>Adobe Analytics tags extension or AppMeasurement.js with server-side forwarding enabled</td>
            <td>
                <ul style="margin-top: 0;">
                    <li>When you want to send Adobe Analytics data to Audience Manager to create segments that can be shared with other Adobe Experience Cloud destinations, people-based destinations, or other device-based and custom destinations supported by Audience Manager.</li>
                </ul>
            </td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Share segments to ad platforms that include behavioral attributes collected in Analytics.</li>
                    <li>Enrich segments with Analytics data to create high-value, cross-channel segments to use in on-site targeting.</li>
                    <li>Layer in Analytics data to segments keyed off on hashed identifiers, such as email, to use in social media platforms.</li>
                </ul>
            </td>
        </tr>        
        <tr>
            <td>
                <a href="https://experienceleague.adobe.com/docs/analytics/integration/audience-analytics/mc-audiences-aam.html" target="_blank" rel="noreferrer">Audience Manager sending data back to Analytics</a>
            </td>
            <td>Adobe Analytics tags extension or AppMeasurement.js with server-side forwarding enabled</td>
            <td>
                <ul style="margin-top: 0;">
                    <li>When you want to share segments from Audience Manager to Analytics to inform audience discovery, segmentation, and optimization.</li>
                </ul>
            </td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Use Audience Manager segments that include demographic data from third-party providers in Analytics reports.</li>
                    <li>Use Audience Manager segments that include campaign data from ad servers in Analytics reports.</li>
                    <li>Use Audience Manager segments that include onboarded CRM data in Analytics reports.</li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>
