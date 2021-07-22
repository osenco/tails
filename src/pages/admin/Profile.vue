<template>
  <div class="bg-white dark:bg-gray-800">
    <div class="container mx-auto my-5 p-5">
      <div class="md:flex no-wrap md:-mx-2">
        <!-- Left Side -->
        <div class="w-full md:w-3/12 md:mx-2">
          <!-- Profile Card -->
          <div class="bg-white p-3 border-t-4 border-green-400">
            <div class="image overflow-hidden">
              <img
                class="h-auto w-full mx-auto"
                src="https://lavinephotography.com.au/wp-content/uploads/2017/01/PROFILE-Photography-112.jpg"
                alt=""
              />
            </div>
            <h1 class="text-gray-900 font-bold text-xl leading-8 my-1">
              Jane Doe
            </h1>
            <h3 class="text-gray-600 font-lg text-semibold leading-6">
              Owner at Her Company Inc.
            </h3>
            <p class="text-sm text-gray-500 hover:text-gray-600 leading-6">
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Reprehenderit, eligendi dolorum sequi illum qui unde aspernatur
              non deserunt
            </p>
            <ul
              class="
                bg-gray-100
                text-gray-600
                hover:text-gray-700
                hover:shadow
                py-2
                px-3
                mt-3
                divide-y
                rounded
                shadow-sm
              "
            >
              <li class="flex items-center py-3">
                <span>Status</span>
                <span class="ml-auto"
                  ><span
                    class="bg-green-500 py-1 px-2 rounded text-white text-sm"
                    >Active</span
                  ></span
                >
              </li>
              <li class="flex items-center py-3">
                <span>Member since</span>
                <span class="ml-auto">Nov 07, 2016</span>
              </li>
            </ul>
          </div>
          <!-- End of profile card -->
        </div>
        <!-- Right Side -->
        <div class="w-full md:w-9/12 mx-2 h-64">
          <!-- Profile tab -->
          <!-- About Section -->
          <div class="bg-white shadow overflow-hidden sm:rounded-lg">
            <div class="px-4 py-5 sm:px-6">
              <h3 class="text-lg leading-6 font-medium text-gray-900">
                Applicant Information
              </h3>
              <p class="mt-1 max-w-2xl text-sm text-gray-500">
                Personal details and application.
              </p>
            </div>
            <div class="border-t border-gray-200">
              <dl>
                <div
                  class="
                    bg-gray-50
                    px-4
                    py-5
                    sm:grid sm:grid-cols-3
                    sm:gap-4
                    sm:px-6
                  "
                >
                  <dt class="text-sm font-medium text-gray-500">Full name</dt>
                  <dd class="mt-1 text-sm text-gray-900 sm:mt-0 sm:col-span-2">
                    Margot Foster
                  </dd>
                </div>
                <div
                  class="
                    bg-white
                    px-4
                    py-5
                    sm:grid sm:grid-cols-3
                    sm:gap-4
                    sm:px-6
                  "
                >
                  <dt class="text-sm font-medium text-gray-500">
                    Application for
                  </dt>
                  <dd class="mt-1 text-sm text-gray-900 sm:mt-0 sm:col-span-2">
                    Backend Developer
                  </dd>
                </div>
                <div
                  class="
                    bg-gray-50
                    px-4
                    py-5
                    sm:grid sm:grid-cols-3
                    sm:gap-4
                    sm:px-6
                  "
                >
                  <dt class="text-sm font-medium text-gray-500">
                    Email address
                  </dt>
                  <dd class="mt-1 text-sm text-gray-900 sm:mt-0 sm:col-span-2">
                    margotfoster@example.com
                  </dd>
                </div>
                <div
                  class="
                    bg-white
                    px-4
                    py-5
                    sm:grid sm:grid-cols-3
                    sm:gap-4
                    sm:px-6
                  "
                >
                  <dt class="text-sm font-medium text-gray-500">
                    Salary expectation
                  </dt>
                  <dd class="mt-1 text-sm text-gray-900 sm:mt-0 sm:col-span-2">
                    $120,000
                  </dd>
                </div>
                <div
                  class="
                    bg-gray-50
                    px-4
                    py-5
                    sm:grid sm:grid-cols-3
                    sm:gap-4
                    sm:px-6
                  "
                >
                  <dt class="text-sm font-medium text-gray-500">About</dt>
                  <dd class="mt-1 text-sm text-gray-900 sm:mt-0 sm:col-span-2">
                    Fugiat ipsum ipsum deserunt culpa aute sint do nostrud anim
                    incididunt cillum culpa consequat. Excepteur qui ipsum
                    aliquip consequat sint. Sit id mollit nulla mollit nostrud
                    in ea officia proident. Irure nostrud pariatur mollit ad
                    adipisicing reprehenderit deserunt qui eu.
                  </dd>
                </div>
                <div
                  class="
                    bg-white
                    px-4
                    py-5
                    sm:grid sm:grid-cols-3
                    sm:gap-4
                    sm:px-6
                  "
                >
                  <dt class="text-sm font-medium text-gray-500">Attachments</dt>
                  <dd class="mt-1 text-sm text-gray-900 sm:mt-0 sm:col-span-2">
                    <ul
                      class="
                        border border-gray-200
                        rounded-md
                        divide-y divide-gray-200
                      "
                    >
                      <li
                        class="
                          pl-3
                          pr-4
                          py-3
                          flex
                          items-center
                          justify-between
                          text-sm
                        "
                      >
                        <div class="w-0 flex-1 flex items-center">
                          <PaperClipIcon
                            class="flex-shrink-0 h-5 w-5 text-gray-400"
                            aria-hidden="true"
                          />
                          <span class="ml-2 flex-1 w-0 truncate">
                            resume_back_end_developer.pdf
                          </span>
                        </div>
                        <div class="ml-4 flex-shrink-0">
                          <a
                            href="#"
                            class="
                              font-medium
                              text-indigo-600
                              hover:text-indigo-500
                            "
                          >
                            Download
                          </a>
                        </div>
                      </li>
                      <li
                        class="
                          pl-3
                          pr-4
                          py-3
                          flex
                          items-center
                          justify-between
                          text-sm
                        "
                      >
                        <div class="w-0 flex-1 flex items-center">
                          <PaperClipIcon
                            class="flex-shrink-0 h-5 w-5 text-gray-400"
                            aria-hidden="true"
                          />
                          <span class="ml-2 flex-1 w-0 truncate">
                            coverletter_back_end_developer.pdf
                          </span>
                        </div>
                        <div class="ml-4 flex-shrink-0">
                          <a
                            href="#"
                            class="
                              font-medium
                              text-indigo-600
                              hover:text-indigo-500
                            "
                          >
                            Download
                          </a>
                        </div>
                      </li>
                    </ul>
                  </dd>
                </div>
              </dl>
            </div>
          </div>
          <!-- End of about section -->

        </div>
      </div>
    </div>
  </div>
</template>

<script>
import { PaperClipIcon } from "@heroicons/vue/solid";

export default {
  components: {
    PaperClipIcon,
  },
};
</script>

<style scoped>
:root {
  --main-color: #4a76a8;
}

.bg-main-color {
  background-color: var(--main-color);
}

.text-main-color {
  color: var(--main-color);
}

.border-main-color {
  border-color: var(--main-color);
}
</style>
