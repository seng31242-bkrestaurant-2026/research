BK Restaurant System
Issue 5: Literature Review
---
1. Introduction
When we started working on the BK Restaurant project, we found that there is already a lot of research and industry work related to the problems faced by restaurant owners like Mr. Sanjeewa across three branches.
Key problems identified in literature:
Manual order handling
Poor delivery visibility
Paper-based records
Lack of system integration
Research and industry studies show that many restaurants face similar challenges, and different systems have been developed to solve them.
This review focuses on understanding:
What works in existing systems
What does not work
How these findings support BK Restaurant System design
---
2. Restaurant Management Systems
Research shows that restaurants benefit significantly when moving from manual to digital systems. Kasavana and Cahill (2007) highlighted that restaurants need integrated systems that connect:
Order management
Billing
Inventory
Customer communication
Instead of using separate tools, everything should be in one system. Later research by Gupta (2016) supports this and found several benefits of digital systems:
Higher order accuracy
Faster table turnover
Improved customer satisfaction
For BK Restaurant:
Each branch currently works independently
There is no central visibility
Owner cannot monitor operations in real time
A key limitation in literature is that: Large enterprise systems exist, but they are often too complex and expensive for small local businesses.
---
3. Online Food Ordering and Delivery
The online food delivery industry has grown rapidly in recent years. According to Statista (2024), the market is rapidly expanding, and growth is driven by:
Smartphone usage
Customer demand for real-time tracking
Pigatto et al. (2017) identified a major issue regarding order coordination problems, where orders come from multiple channels such as Phone, WhatsApp, and Apps. This often leads to missed or duplicated orders, which directly matches BK Restaurant's current situation.
Key findings:
Customers now expect:
Real-time tracking
Accurate delivery estimates
This supports the inclusion of GPS-based rider tracking and real-time order updates in the proposed system.
---
4. Point of Sale (POS) Systems
POS systems are central to modern restaurant operations. Dixon et al. (2020) explain that modern cloud POS systems:
Record sales in real time
Automatically update inventory
Generate reports instantly
For multi-branch systems, the owner can compare performance across branches with no need for manual reporting. However, Weerasinghe (2021) found that many SME restaurants face issues with existing POS tools due to:
High cost
Complex interfaces
Lack of local customization
Therefore, for BK Restaurant, a custom POS system is more suitable.
---
5. Real-Time Delivery Tracking
Research in logistics shows that GPS tracking improves delivery performance. Boysen et al. (2021) found that the benefits of real-time tracking include:
Reduced delivery delays
Better route planning
Improved efficiency
Google Maps SDK supports live tracking, route optimization, and ETA calculation. For BK Restaurant, this supports the implementation of a rider mobile app with GPS tracking and live delivery status updates.
---
6. Inventory Management
Research shows automation improves inventory control. Heizer et al. (2019) found that automated inventory systems:
Reduce food waste
Improve cost control
Key principle: When a sale happens, inventory should update automatically. The National Restaurant Association (2023) recommends the integration of POS, inventory, and supplier ordering.
For BK Restaurant:
Current system is fully manual
No real-time stock visibility
Proposed system benefits:
Auto stock updates
Low-stock alerts
Supplier notifications
---
7. Multi-Branch Management
Managing multiple branches is a common challenge in hospitality. Law et al. (2013) found that best-performing businesses use:
Centralized dashboards
Real-time reporting
Key benefits:
Compare branch performance
Track revenue trends
Data-driven decisions
For BK Restaurant:
3 branches in different locations
Currently no centralized system
Literature strongly supports the implementation of a central owner dashboard and a unified reporting system.
---
8. Technology Stack Considerations
Literature supports the chosen technology stack:
React.js: Best for dynamic dashboards, utilizing a component-based UI (Aggarwal, 2018).
Flutter: Ideal for cross-platform mobile development using a single codebase for Android + iOS (Google Developers, 2023).
Node.js: Efficiently handles multiple concurrent requests and is highly suitable for real-time updates (Tilkov & Vinoski, 2010).
PostgreSQL: Offers strong relational database support to handle complex data relationships such as orders, inventory, and branches.
---
9. Summary of Key Findings
Integrated systems reduce order errors.
Real-time tracking improves delivery efficiency.
Custom systems are better for small businesses than complex enterprise tools.
Automated inventory reduces waste and improves control.
Multi-branch dashboards support better data-driven decision-making.
The proposed technology stack is well-supported in industry literature.
---
10. References
Aggarwal, S. (2018). Modern Web Development with React. Packt Publishing.
Boysen, N., Fedtke, S., & Schwerdfeger, S. (2021). Last-mile delivery concepts: a survey from an operational research perspective. OR Spectrum, 43, 1-58.
Dixon, M., Freeman, K., & Toman, N. (2020). Digital POS systems and their impact on restaurant operations. Cornell Hospitality Quarterly, 61(2), 45-60.
Google Developers. (2023). Flutter: Build apps for any screen. https://flutter.dev
Gupta, S. (2016). The impact of technology on restaurant operations. International Journal of Hospitality Management, 55, 91-102.
Heizer, J., Render, B., & Munson, C. (2019). Operations Management: Sustainability and Supply Chain Management (13th ed.). Pearson.
Kasavana, M. L., & Cahill, J. J. (2007). Managing Computers in the Hospitality Industry (5th ed.). American Hotel & Lodging Educational Institute.
Law, R., Buhalis, D., & Cobanoglu, C. (2013). Progress on information and communication technologies in hospitality and tourism. International Journal of Contemporary Hospitality Management, 26(5), 727-750.
National Restaurant Association. (2023). Restaurant Technology Landscape Report 2023. https://restaurant.org
Pigatto, G., Machado, J. G. C. F., Negreti, A. S., & Machado, L. M. (2017). Have you chosen your request? Analysis of online food delivery companies in Brazil. British Food Journal, 119(3), 639-657.
Statista. (2024). Online food delivery market worldwide. https://www.statista.com
Tilkov, S., & Vinoski, S. (2010). Node.js: Using JavaScript to build high-performance network programs. IEEE Internet Computing, 14(6), 80-83.
Weerasinghe, P. (2021). Digital transformation challenges for SME restaurants in South Asia. Journal of Hospitality and Tourism Technology, 12(1), 112-128.