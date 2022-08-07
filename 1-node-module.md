// To export a function or variable from a module

module.exports.new_function_name = old_function_name;       // If multiple functions or varaibles to be exported

module.exports = old_function_name;      // If one function to be exported


// To import a module

require(./name.js).new_function_name;     // If multiple functions or varaibles to be exported

const _name = require(./name.js);
_name();      //  If one function to be exported
