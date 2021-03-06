# [5/9] How to guide your customers: creating a menu

Alright! Time to add meaningful conversations to your chatbot. Up until now, you've created a small and talkative chatbot but every chatbot needs to have its purpose.

The purpose of your Starman chatbot is to:
- Show NASA's Astronomy Picture of the Day
- Display photos from NASA Mars rovers (Curiosity, Opportunity, Spirit)
- Show the current position of the International Space Station
- Display how many people are in the space right now
- Show upcoming SpaceX launches

**Your task is** now is to organize this information so that you display each of the information details when the user asks for it. The best way to do it is in the form of menus. This means you will have to implement a starting menu with a listing of the content user can get from your chatbot. Also in the case of photos from NASA's Mars rovers, you will have an additional submenu, because each of the rovers have different sets of photos. That will cause you to have an another submenu.

Show menu whenever user types "menu" or when Dialogflow is not able to answer to users input.

## Tips

Here are a few tips that can help you to do this exercise:

- Build a menu using Facebook Messenger's [Generic template](https://developers.facebook.com/docs/messenger-platform/reference/template/generic).
- Use Claudia Bot Builder's Message builder for builing this menu. See [documentation for more info and help](https://github.com/claudiajs/claudia-bot-builder/blob/master/docs/FB_TEMPLATE_MESSAGE_BUILDER.md).
- Here are some images you can use for your menu: [folder with images](../assets/menu).
- You can see an example of the menu in Space Explorer bot video here: https://vimeo.com/172001135.

------

[![Next](../assets/next.png)](./exercise-06.md)

or [go back](../exercise-04.md).