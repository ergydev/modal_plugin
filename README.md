# modal_plugin
Documentation du Plugin de Modal React

Introduction 

Modal plugin React to display an easy customizable modal in your React application. 

Installation 

To install this modal you can use npm : 

npm install modal_plugin

Utilisation 

You need to create a state for the modal to know when it's open like this : 
`const [modalOpen, setModalOpen] = useState(false)`

the you create a function to open the Modal and close it :
const handleOpenModal = () => {
    setModalOpen(true);
};

const handleCloseModal = () => {
    setModalOpen(false);
}

Opening 

The simplest approach is to add onClick={handleOpenModal} on the DOM element that you want to use, like a button or a link.

Closing 
Similar to how we did with the opening we'll add onClose={handleCloseModal} if the modal it's already open. 

