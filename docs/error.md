

export const FancyButton = ({ text = "Press" }) => {
  return (
    <button onClick={() => console.log(text)}>{text}</button>
  )
}

<FancyButton text="Foo" />
