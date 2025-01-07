# React Router v6 Nested Routes and Wildcard Route Issue

This repository demonstrates an unexpected behavior in React Router v6 when using nested routes in conjunction with a wildcard route ('*'). The wildcard route seems to match before other defined routes, leading to an incorrect component being rendered.  This is unexpected, as the wildcard route is intended to catch any unmatched routes.