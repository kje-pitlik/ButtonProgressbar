# ButtonProgressbar

## Class Definition

### `public class ButtonProgressbar: UIButton`

Represents a custom button with a progress bar.

#### Properties

- `private var progressLayer: CAShapeLayer!`
- `private var startAngle: CGFloat!`
- `private var progressColor: CGColor!`
- `public var pos: Position!`

#### Initializer

##### `public init(frame: CGRect, start: Float, pos: Position, cornerRadius: Double, borderWidth: Double, borderColor: CGColor, progressColor: CGColor)`

Initializes a ButtonProgressbar with the specified parameters.

###### Parameters

- `frame`: The frame rectangle for the button progress bar.
- `start`: The start value for the progress bar.
- `pos`: The position of the progress bar.
- `cornerRadius`: The corner radius of the button progress bar.
- `borderWidth`: The border width of the button progress bar.
- `borderColor`: The border color of the button progress bar.
- `progressColor`: The progress color of the button progress bar.

#### Methods

##### `public func setProgress(_ progress: Double)`

Sets the progress of the button progress bar.

###### Parameters

- `progress`: The progress value to set. Should be between 0.0 and 1.0.

##### `public override func layoutSubviews()`

Overrides the layoutSubviews method of the UIButton class.

#### Enumerations

##### `public enum Position`

Represents the position options for the button progress bar.

###### Cases

- `left`
- `right`
- `top`
- `bottom`
