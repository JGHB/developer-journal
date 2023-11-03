# Learning Entry - 2023-11-03

  ## Type of Learning: Snippet
  
  ### What I've Learned:
  
  If you want to style rext rows so you have text on one side of a column and other text on the opposite side, and you want some styling of the space in between, you can use the tailwind bottom border properties to add dotted or dashed lines to maintain the visual of the row while elements within the row are father apart.

  ```js
    <div key={listing.address} className="flex flex-row items-center">
      <div className='text-n whitespace-nowrap overflow-hidden text-overflow-ellipsis max-w-xs'>{listing.address}</div>
      <div className="border-dotted border-b-2 pt-2.5 border-black flex-grow"/>
      <div>{listing.price}</div>
    </div>
  ```