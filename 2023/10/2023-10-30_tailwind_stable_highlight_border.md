# Learning Entry - 2023-10-30

  ## Type of Learning: Snippet
  
  ### What I've Learned:
  
  If you want an element styled with tailwind to have a highlighted border on hover, adding one on hover will change the size of the element and cause the page layout to shift slightly if surrounded by other elements. This can be solved by applying a translucent border of the same thickness to the element as its default state.

  ```js
    <img
      src={imageUrl}
      alt="APOD"
      className="rounded-lg h-10 border-transparent border-2 hover:border-yellow-500 cursor-pointer sm:h-12"
      onClick={() => sendImageMessage()}
    />
  ```