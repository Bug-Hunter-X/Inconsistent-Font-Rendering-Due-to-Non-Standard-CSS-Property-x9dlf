# Inconsistent Font Rendering Due to Non-Standard CSS Property

This repository demonstrates a common, yet often overlooked, CSS bug involving the use of a non-standard property: `font-size-adjust`.

The `bug.css` file contains the problematic code, while `bugSolution.css` provides the corrected version.

The issue arises from the use of `font-size-adjust`, a property that is not widely supported and may lead to inconsistencies in font rendering across different browsers.  Some browsers may ignore it, while others may interpret it differently, resulting in unexpected visual outcomes.

The solution involves removing the `font-size-adjust` property and potentially using alternative techniques to achieve the desired effect, if necessary, such as using a specific font family or adjusting other font properties like `font-stretch`.  The solution presented here prioritizes cross-browser compatibility and consistency.