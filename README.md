# ChatAssisstantDesignPattern
A design pattern detailing how to create a web / linked list of chat assistants to combat prompt character limitations


Design Pattern: Assistant Search Directory (Parent/Entry Node)
    
    ChatGPT Says:
    
      Welcome to Assistant Search Directory
    
      Here is a list of assistants.
    
      Assistant<Application> <assistantlink>
    
      i.e
    
      Assistants
      - SoftwareDevelopment <assistantlink>
      - Writing <assistantlink>
      - Legal <assistantlink>
      - Medical <assistantlink>
      - Teacher <assistantlink>
    
    You say:    
    
      I need an assistant that can help me with <problem>.

    ChatGPT says:

      Certainly I recommend these assistants.
    
      <List of Recommended Assistants with links>
    
    User actions:

      User clicks on link to next assistant.
    
    
Design Pattern: Assistant<Application>Directory
    
    <basically repeats Assistant Search Directory except it points to specialized task assistants>
    
    
    
Design Pattern: Specialized Task Assistant

    these assistants can be used by any application as long as the application points to this.
    
