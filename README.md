# OSM-Hackfest-uv-react
# Utopian Vision
## Team_Pollyanna (Nirjal Bhurtel, Bikraj Shrestha, Dipen Khatri, Priyanshu Sharma)

## Idea:

The United Nations General Assembly approved a proposal to upgrade Nepal from the least developed country category to the developing country category by December 2026.

As the stakes are high and time is limited, there is no room for mistakes while conducting developmental activities. Unplanned development conducted in developing countries like Nepal for a very long period of time has become problematic in organizing and planning the developmental works. Long-run development and sustainability have become major concerns in the process of infrastructural and structural development in such countries. At the present we have two choices in order to achieve this :
First, demolish the unplanned structures and replan the development starting all over again. Secondly, we can improvise on what we have. The former one could be a better idea for developing a utopian nation. But the question is, “Is it really possible?”
No, it isn’t ... especially for a country like Nepal which almost took a decade to overcome the earthquake destruction. Improvising on what we have seems to be the most practical choice.
But another question arises here, If improvisations could have been made then why aren’t the developing countries taking necessary initiatives? We had conducted some research and found that governmental and non-governmental organizations were not as concerned about these issues as they should be. The public is not aware of the impacts created by these unplanned developmental activities in the long term. If we do not stop now and continue practicing unplanned development then the impacts caused would be irreversible. For example: If industries are constructed on land suitable for agriculture then solving that issue would take another century. Therefore, this is the time to take action and change the face of development. Where do we start from? It is not feasible for the government to enforce new rules on the citizens within a short period of time for the purpose of planned development. However, the government can still work on the infrastructures they are going to build in the public areas.Our team looks forward to simplifying this planning process.

Our Idea
Our team has come up with the idea of creating an online map locating the appropriate areas for the developmental works following the principles of sustainable development with the vision of creating a utopian nation.UV, our web application, is built on top of react js frontend with Django as backend.
GeoPandas is used for processing whereas the map turf library of npm is used for the mapping purpose in react js.
Sustainable development is the major motto of this project. We are eager to help the government establish planned cities having access to essential facilities and services without compromising the environmental condition.In the current context, there are several governmental places that can be utilized for the construction of parks, hospitals, and schools. In order to locate these appropriate areas, a community is considered as a point and circular buffer zone with an appropriate radius with center at that point being drawn. Appropriate areas for the proposed infrastructures such as hospitals, schools and parks are located according to this reference point. A governmental area that lies at the intersection of the maximum number of buffer zones needs to have a hospital if there doesn’t exist one near 5 km. Schools should be constructed far from the industrial area and highways in quiet spaces within a radius of 1.63 km from the point, one park per community should be constructed, proper management of waste and easily accessible public toilets should be constructed through analysis. We are going to map all the governmental areas and analyze the free spaces available for developmental works. The map will not just contain proposed places but also addresses the need for proposed infrastructures suitable there.
Therefore, UV is an innovation that strives towards development of a utopian nation.

## Problem to be Adressed:

Sustainable development is the long-term development of improving the quality of life in a city, including ecological, cultural, political, institutional, social, and economic components without leaving a burden over the future generations. For sustainable development, a nation should follow certain development criteria. But, even in the 21st era, sustainable development is only limited to the pages of 5th graders' books, because of the ignorance of governmental and non governmental organization and unawareness of people about the long term benefits. The result of all the ignorance is the unplanned development which does not take sustainable development’s criterias into consideration. Due to this, there are different problems that can occur which can be solved if we plan for a better city by considering sustainable development criteria.
The criteria required for sustainable development are:

### Health:

Health is an important aspect of any human’s life. Health determines how a human functions in his/her day-to-day life. An essential requirement of maintaining good health is hospitals. Hospitals in sustainable cities should be within a reachable distance from any community. A hospital should be easily accessible by roadways.WHO recommends that any health facility from a community should be within a 5 km distance.

### Education:

Despite the Sustainable Development Goal to have every child in school and learning by 2030, there are still 260 million children who don't go to primary or secondary school. It is not beyond our power to create a world in which all children have access to a good education. As Nelson Mandala stated, a world where each and every one of the children has access to a good education is definitely possible. So, accessibility to a good education is a must in a sustainable city. Sabean (2007) on reviewing the distance from home to school suggested that for school students, the maximum distance from home to school should be 3 kilometers. A school within a reachable distance is not the only criteria to be fulfilled, there should also be enough students in a school.

### Green Parks:

In the hectic life of the 21st-century, people lack social interactions. Due to less social interaction, people are suffering from different disorders and lack social skills. A 2018 study from Harvard Chan School followed more than 9,000 U.S. adolescents ages 12-18. It showed that adolescents who live in areas surrounded by green space had a lower chance of depressive symptoms than those living in dense urban areas. To address this issue, a sustainable city should have green parks, children's playgrounds, and old age recreational parks in each community.

### Public Toilets:

Access to sustainable and safe public sanitation improves hygiene practices, which leads to improved health and quality of life for men and women. Public sanitation should be easily available in parks, parking areas, and places where public vehicles stop for the passengers to get on board and disembark.

### Landfills:

In the context of underdeveloped countries, there is no proper urban planning and coordination among concerned authorities which eventually affects our ecological diversity, environment and health. In unplanned planning there is rapid urbanization and industrialization growth which limits access to basic infrastructure, hospitals, and quality essential services as mentioned above. Our web application will inform people about the possible development necessary in their community and also provides factual information for governmental and non governmental organization, so they can work towards achieving sustainable development.

# Future Improvements:
- Machine Learning Optimization
- Increase the data that can be analyzed
- Include isochrone API to build a  buffer according to the user's reach
- Analyze raster data ( For population, pollution, elevation and slope analysis )
- Build the  commercial facilitating application

# Presentaion:
https://www.canva.com/design/DAFgjyPmc7w/Fc30pS9IDDvhe1PHLEU6AQ/edit?utm_content=DAFgjyPmc7w&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton
