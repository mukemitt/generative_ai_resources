1. https://langchain-ai.github.io/langgraph/tutorials/introduction/
2. Tutorial: Python typing module - Use type checkers effectively (https://www.digitalocean.com/community/tutorials/python-typing-module)
3. https://docs.python.org/3/library/typing.html
4. https://mypy.readthedocs.io/en/stable/cheat_sheet_py3.html
5. https://stackoverflow.com/questions/71898644/how-to-use-python-typing-annotated
   Annotated in python allows developers to declare the type of a reference and provide additional information related to it.
   name = Annotated[str, "first letter is capital"]
   This tells that name is of type str and that name[0] is a capital letter.

On its own Annotated does not do anything other than assigning extra information (metadata) to a reference. It is up to another code, which can be a library, framework or your own code, to interpret the metadata and make use of it.

7. Class-based syntax https://mypy.readthedocs.io/en/stable/typed_dict.html#class-based-syntax
