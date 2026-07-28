# PicPorter  
**Your open source pipeline for files, images, and video.**

PicPorter is an AGPL 3.0+ open source uploader designed for seamless drag and drop media handling across blogs, forums, platforms, and custom applications. It supports images, videos, and general file uploads with a secure and flexible architecture built for easy integration.

PicPorter is intended to be lightweight, extensible, and adaptable for integrations ranging from small personal sites to enterprise-grade platforms.

---

# PicPorter Feature List

PicPorter is an open source drag-and-drop uploader designed for images, videos, and general file handling across blogs, forums, and web platforms. It is built to be flexible, secure, and easy to integrate into any modern web application.

---

## Core Upload Features

- Drag-and-drop file upload interface
- Click-to-upload fallback support
- Multiple file upload support in a single session
- Support for images, videos, and general file types
- Configurable file type restrictions
- Configurable file size limits
- Batch upload handling for large sets of files

---

## Media Support

- Image upload support (JPG, PNG, WEBP, GIF, and more)
- Video upload support (MP4, WEBM, MOV, and more)
- Document and file upload support (PDF, DOCX, TXT, and more)
- Automatic file type detection
- MIME type validation for security

---

## User Experience Features

- Real-time upload progress indicators
- Visual drag-and-drop zone highlighting
- File preview before upload (images and videos)
- Upload status feedback (success and failure states)
- Responsive design for mobile and desktop use
- Simple and intuitive interface for end users

---

## Backend & Processing Features

- Secure file handling on the server side
- Configurable storage system (local or cloud-based)
- Automatic file renaming to prevent collisions
- Organized upload directory structure
- Server-side validation of all incoming files
- Support for scalable upload pipelines

---

## Integration Features

- Easy embedding into blogs and CMS platforms
- Forum integration ready design
- API-ready upload endpoints for custom applications
- Frontend and backend separation for flexible deployment
- Framework compatible design (React, Vue, or vanilla JS support)

---

## Security Features

- File type validation on both client and server
- File size restrictions to prevent abuse
- Safe file naming to prevent overwrite attacks
- Upload endpoint protection ready for authentication layers
- Designed to support malware scanning integration

---

## Developer Features

- Modular architecture for easy customization
- Open source AGPL 3.0+ license compliance
- Clean separation between frontend and backend logic
- Easily extendable upload pipeline
- Documentation-ready structure
- GitLab-friendly repository organization

---

## Optional Advanced Features (Planned or Extendable)

- Cloud storage integration (S3, Firebase, etc.)
- Upload retry system for failed transfers
- File reordering before upload
- Thumbnail generation for videos and documents
- User authentication integration support
- Rate limiting and abuse prevention systems
- Multi-language support for global platforms

---

## How PicPorter Works (Explained Without Code)

To use PicPorter on a website:

1. A drop zone area is placed on the page where users can drag files or tap to select them.
2. The browser gathers the chosen files and prepares them for upload.
3. The files are sent to the server using standard web requests.
4. The server stores the files either on the local system or in cloud storage, depending on configuration.
5. The server responds with confirmation information that the site can use to display results to the user.

On the backend:

- A storage directory or cloud bucket is configured.  
- Files are validated to ensure they meet platform requirements.  
- Naming rules prevent collisions.  
- Responses include references the platform can use to embed or access uploaded files.

This explanation allows users to understand the system’s flow without needing code examples.

---

## Installation Overview (Explained Without Code)

To install PicPorter:

1. The repository is cloned from GitLab.  
2. The client folder is opened to configure any visual or layout preferences.  
3. The server folder is opened to configure storage location, accepted file types, or limits.  
4. Dependencies for the server are installed through the standard package manager for the chosen language.  
5. The server is started using the appropriate command for your environment.  
6. The client uploader is linked to the server address so they can communicate.

Each step can be completed with standard commands for the environment you use, replacing specific instructions with descriptive steps to maintain clarity across operating systems.

---

## Configuration

PicPorter can be customized for:

### Storage Options
- Local storage for smaller projects  
- Network storage for distributed systems  
- Cloud storage for scalable deployments  

### Validation Rules  
You may configure accepted:  
- File types  
- File size limits  
- Maximum number of uploads  
- Preview rules  

### Integration Targets
PicPorter can be embedded into:  
- Forums  
- Blogs  
- CMS platforms  
- Admin dashboards  
- Custom applications  

---

## Contributing

Contributions are welcome under the AGPL 3.0+ license.

To contribute:

1. Fork the repository.  
2. Create a feature branch.  
3. Make changes and include documentation when needed.  
4. Submit a merge request through GitLab.  

---

## Specification Branding License (SBL)

### Standard
- Fully AGPL-3.0+ compliant system
- Copyleft enforced for network deployments
- Required attribution:
  - Roxanne Ardary
  - https://www.roxanneardary.com/

### Optional

- **Specification Branding License (SBL)**
  - Attribution-free commercial deployment
  - Pricing based on scale, usage, and deployment scope
  - [https://roxanneardary.com/picporter/](https://roxanneardary.com/picporter/)

---

## License & Notice Requirements

PicPorter is released under the **GNU Affero General Public License v3.0 or later (AGPL-3.0+)**.   
By contributing to this project, you agree that your contributions will also be released under this license.

Please note the following:

- All contributions must comply with the **AGPL-3.0+** terms.  
- Under **Section 7** of the license, all redistributions, forks, and derivative works must preserve attribution to:  
  **Roxanne Ardary** and **[roxanneardary.com](https://www.roxanneardary.com/)**.  
- PicPorter specifications are free to use with attribution. A Specification Branding License can be negotiated upon request.
- The project's **notice.md** file tracks attribution requirements and contributor acknowledgments.  
  Any update that adds new contributors or modifies attribution should also update `notice.md`.
- When submitting a pull request, ensure that any new files maintain the attribution headers where applicable.
- Network-deployed versions of this software must also remain fully AGPL-3.0+ compliant, including exposure of source code modifications when applicable under the license.

For full legal details, please refer to the AGPL-3.0+ license and the project's `notice.md` file.
---

## Author

Created by **Roxanne Ardary**  
Website: **[roxanneardary.com](https://www.roxanneardary.com/)**  
