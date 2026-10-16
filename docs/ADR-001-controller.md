# Keep the professor controller intact

The supplied component exposes Move(float,bool,bool) but contains no keyboard polling. On this task John explicitly authorized a separate input script. Call the existing movement API from that script; preserve the controller's contents, filename and class name.
