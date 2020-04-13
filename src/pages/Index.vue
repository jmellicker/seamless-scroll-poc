<template>
  <q-page class="flex flex-center">
    <div>
      <vue-seamless-scroll :data="listData" :class-option="classOption" class="warp">
        Back in 2017, Michael Osterholm, the director of the Center for Infectious Disease Research and Policy at the University of Minnesota told Time magazine that “We are sitting on something big with H7N9 [bird flu],” and “Any one of these cases could trigger something big. By then it’d be way too late.”

Looking back now, it looks like a lot of other people had warned that it was just a matter of time before a pandemic of the COVID-19 scale took place. And if the government had been prepared and if it didn’t get in the way of the ability of the private sector both to prepare and to respond, the impact of this COVID-19 pandemic on American lives and the economy would have been much smaller than anything we are experiencing right now.

The lack of preparedness at every level of government (federal, state, and local) has nothing to do with a lack of funding or inadequate staffing. Instead, it has everything to do with governments’ bloat, mismanagement, cronyism, and poor focus.

That’s particularly true of the Centers for Disease Control (CDC). In theory, the prevention of diseases like this one is the agency’s entire reason d’être. It is right there in its name “Disease Control.” Its mission statement page also makes the centrality of this goal clear. It states as its priority “confronting global disease threats through advanced computing and lab analysis of huge amounts of data to quickly find solutions.” 

Apparently, not really.

While there is a lot of blame to go around, it is no secret how much the CDC is to blame for the country’s lack of preparedness to take on the coronavirus (followed very closely in ineptitude by the Food and Drug Administration). The agency’s failure to understand the severity of this virus, to provide useful advice to the American people and to political leaders, and to deliver appropriate testing capabilities has been widely documented.

As I wrote last week, emails reveal that weeks after the virus started roaming freely in the U.S., CDC director Dr. Robert Redfield told his employees that “the virus isn’t spreading in the US at this time.” But a month later, the CDC was still telling state and local officials that its “testing capacity is more than adequate to meet current testing demands.” 

It wasn’t.

In this piece, the WSJ reported on three distinct failures made by the agency (helped by the FDA).

“CDC officials botched an initial test kit developed in an agency lab, retracting many tests. They resisted calls from state officials and medical providers to broaden testing, and health officials failed to coordinate with outside companies to ensure needed test-kit supplies, such as nasal swabs and chemical reagents, would be available, according to suppliers and health officials…

“This was kind of a perfect storm of three separate failures,” said Tom Frieden, who directed the CDC from 2009 to 2017, citing the botched test, overstrict FDA rules and sidelined private labs.”

By now, every major newspaper has reported on the incredible failure of the CDC during this crisis. Here is the tidbit from the Washington Post:

“The most consequential failure involved a breakdown in efforts to develop a diagnostic test that could be mass produced and distributed across the United States, enabling agencies to map early outbreaks of the disease, and impose quarantine measures to contain them.”

And as if this weren’t enough failure for one agency, the CDC continues to give the public bad advice and get in the way of our ability to protect ourselves with masks and other needed medical supplies.

Messing up is not a new thing for the CDC. However, unlike what its employees and political allies like to claim, the agency’s poor record and its lack of preparedness has nothing to do with a lack of funding. From 2004 to 2018, total CDC spending grew by over 30 percent, from $8.3 billion to $11.1 billion. Unfortunately, the vast majority of this growth in spending—shock!—did not go to pandemic prevention and protection from COVID-19.

For instance, funding for its National Center for Emerging and Zoonotic Infectious Diseases—which aims to prevent diseases like Ebola—received only $514 million in 2018, a tiny sliver (less than 5%) of total CDC funding. And less than half of that $514 million went to emerging diseases like COVID-19. The rest of that budget is spent on stuff like chronic fatigue.

Meanwhile, funding for the CDC’s chronic-disease programs—which aim to prevent smoking, alcohol consumption, and poor diets—received nearly $1 billion over that same time, almost double the funding for infectious-disease prevention. As Michelle Minton at the Competitive Enterprise Institute notes in a must-read piece, more money goes to efforts like “environmental health ($180 million), injury prevention ($270 million), and occupational safety ($330 million).” All these projects are also funded by other agencies.

And, of course, let’s not forget the large amount of time the CDC (along with its companion in failure, the FDA) spends on alarming everyone about youth vaping. It is not an epidemic, it’s not contagious but it’s certainly got plenty of attention from the CDC, and the FDA. Isn’t it obvious now that these busybody government bureaucrats should have focused their efforts instead on fighting and preventing actual, real-world epidemics—you know, of the contagious type.

Being a policy analyst following the action of various government agencies and trying to hold them accountable feels like being a broken record. An emergency happens, we write about the incompetence of various government agencies in their response, and then nothing changes. And indeed, many of us wrote about the CDC’s failures during the last Ebola outbreak and the many others before that. But here we are again. 

This time, however, these government failures have resulted in millions of Americans being all stuck in their homes, schools being closed, the economy in a recession, and 18,000 people having died so far.

Hopefully this time will be different because of the scale of the impact of the failures. But I’m not holding my breath—which is hopefully free of COVID-19.
      </vue-seamless-scroll>
    </div>
  </q-page>
</template>

<script>
import vueSeamless from "vue-seamless-scroll";
import c from '@jmellicker/jlogs'

export default {
  data() {
    return {
      listData: [
        { text: "something" },
        { text: "something" },
        { text: "something" },
        { text: "something" },
        { text: "something" },
        { text: "something" },
        { text: "something" },
        { text: "something" },
        { text: "something" }
      ]
    };
  },
  computed: {
    classOption: function() {
      return {
        step: 4,
        limitMoveNum: 2,
        hoverStop: false
      };
    }
  },
  components: {
    vueSeamless
  }
};
</script>
<style>
.warp {
  height: 80vh;
  width: 80vw;
  overflow: hidden;
  font-size: 8rem;
  line-height: 10rem;
}

.warp ul {
  list-style: none;
  padding: 0;
  margin: 0 auto;
}

.warp li {
  height: 30px;
  line-height: 30px;
  display: flex;
  justify-content: space-between;
  font-size: 15px;
}
</style>