1. *Aliaksandr, Konan*
2. Minsk, **Belarus**, newalex1985@tut.by
3. Hello, my name is Aliaksandr Konan. My goal is to study JS. I like to solve technical problems. I set goals for myself and put the maximum amount of effort to achieve of it. Solving complex problems, continuous self-development gives me pleasure and allows me to find self-realization in life.
4. *JavaScript(ES5/ES2015)*, *React-Redux*, *Git*, *Agile-Scrum*, *1C Development*. *C*, *Asm* for embedded systems.
5. ```
	  import React, { Component } from 'react';
      import { PersonDetails, PersonList } from '../sw-components';
      import Row from '../row';

      export default class PeoplePage extends Component {

        state = {
          selectedItem: null
        };

        onItemSelected = (selectedItem) => {
          this.setState({ selectedItem });
        };

        render() {
          const { selectedItem } = this.state;

          return (
            <Row
              left={<PersonList onItemSelected={this.onItemSelected} />}
              right={<PersonDetails itemId={selectedItem} />} />
          );
        }
      }

   ```
6. Portfolio (projects): https://newalex1985.github.io/presentations/cv/.
7. **Belarusian State University of Informatics and Radioelectronics**, **Belarusian State Economic University**, **The Rolling Scopes School/RS 2019 Q1 (JavaScript)**, continuous self-education.
8. **Pre-intermediate**. Previously I took some courses, currently I'm engaged in self-education, in the future I plan to go on the English courses.