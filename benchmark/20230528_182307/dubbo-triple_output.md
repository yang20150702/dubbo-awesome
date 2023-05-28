# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.076 ops/ms
# Warmup Iteration   2: 2.549 ops/ms
# Warmup Iteration   3: 5.546 ops/ms
Iteration   1: 6.020 ops/ms
Iteration   2: 6.458 ops/ms
Iteration   3: 6.240 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.239 ±(99.9%) 3.996 ops/ms [Average]
  (min, avg, max) = (6.020, 6.239, 6.458), stdev = 0.219
  CI (99.9%): [2.243, 10.235] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.385 ops/ms
# Warmup Iteration   2: 4.687 ops/ms
# Warmup Iteration   3: 5.728 ops/ms
Iteration   1: 5.765 ops/ms
Iteration   2: 5.984 ops/ms
Iteration   3: 5.899 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.883 ±(99.9%) 2.009 ops/ms [Average]
  (min, avg, max) = (5.765, 5.883, 5.984), stdev = 0.110
  CI (99.9%): [3.873, 7.892] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.561 ops/ms
# Warmup Iteration   2: 5.243 ops/ms
# Warmup Iteration   3: 6.132 ops/ms
Iteration   1: 6.176 ops/ms
Iteration   2: 6.139 ops/ms
Iteration   3: 5.950 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.088 ±(99.9%) 2.205 ops/ms [Average]
  (min, avg, max) = (5.950, 6.088, 6.176), stdev = 0.121
  CI (99.9%): [3.883, 8.293] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.787 ops/ms
# Warmup Iteration   2: 4.205 ops/ms
# Warmup Iteration   3: 5.738 ops/ms
Iteration   1: 5.885 ops/ms
Iteration   2: 5.509 ops/ms
Iteration   3: 5.700 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.698 ±(99.9%) 3.427 ops/ms [Average]
  (min, avg, max) = (5.509, 5.698, 5.885), stdev = 0.188
  CI (99.9%): [2.271, 9.125] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 17.345 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.850 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.364 ±(99.9%) 0.005 ms/op
Iteration   1: 4.900 ±(99.9%) 0.011 ms/op
Iteration   2: 4.876 ±(99.9%) 0.013 ms/op
Iteration   3: 4.881 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.886 ±(99.9%) 0.229 ms/op [Average]
  (min, avg, max) = (4.876, 4.886, 4.900), stdev = 0.013
  CI (99.9%): [4.657, 5.114] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 15.680 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.284 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.815 ±(99.9%) 0.006 ms/op
Iteration   1: 5.241 ±(99.9%) 0.010 ms/op
Iteration   2: 5.248 ±(99.9%) 0.010 ms/op
Iteration   3: 5.286 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.259 ±(99.9%) 0.444 ms/op [Average]
  (min, avg, max) = (5.241, 5.259, 5.286), stdev = 0.024
  CI (99.9%): [4.815, 5.702] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 17.996 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 6.608 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.442 ±(99.9%) 0.007 ms/op
Iteration   1: 5.216 ±(99.9%) 0.010 ms/op
Iteration   2: 5.352 ±(99.9%) 0.011 ms/op
Iteration   3: 5.098 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.222 ±(99.9%) 2.319 ms/op [Average]
  (min, avg, max) = (5.098, 5.222, 5.352), stdev = 0.127
  CI (99.9%): [2.902, 7.541] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 17.893 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 6.281 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.627 ±(99.9%) 0.015 ms/op
Iteration   1: 5.261 ±(99.9%) 0.018 ms/op
Iteration   2: 5.575 ±(99.9%) 0.013 ms/op
Iteration   3: 5.583 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.473 ±(99.9%) 3.346 ms/op [Average]
  (min, avg, max) = (5.261, 5.473, 5.583), stdev = 0.183
  CI (99.9%): [2.127, 8.819] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 15.586 ±(99.9%) 0.226 ms/op
# Warmup Iteration   2: 5.792 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.557 ±(99.9%) 0.027 ms/op
Iteration   1: 4.915 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.060 ms/op
                 createUser·p0.50:   4.620 ms/op
                 createUser·p0.90:   6.177 ms/op
                 createUser·p0.95:   7.053 ms/op
                 createUser·p0.99:   9.503 ms/op
                 createUser·p0.999:  16.733 ms/op
                 createUser·p0.9999: 25.805 ms/op
                 createUser·p1.00:   27.886 ms/op

Iteration   2: 5.109 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.032 ms/op
                 createUser·p0.50:   4.891 ms/op
                 createUser·p0.90:   6.346 ms/op
                 createUser·p0.95:   6.947 ms/op
                 createUser·p0.99:   9.094 ms/op
                 createUser·p0.999:  26.379 ms/op
                 createUser·p0.9999: 30.106 ms/op
                 createUser·p1.00:   30.769 ms/op

Iteration   3: 5.096 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.040 ms/op
                 createUser·p0.50:   4.850 ms/op
                 createUser·p0.90:   6.250 ms/op
                 createUser·p0.95:   7.141 ms/op
                 createUser·p0.99:   9.961 ms/op
                 createUser·p0.999:  28.475 ms/op
                 createUser·p0.9999: 33.063 ms/op
                 createUser·p1.00:   33.292 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 190437
  mean =      5.039 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 94 
    [ 2.500,  5.000) = 113539 
    [ 5.000,  7.500) = 70112 
    [ 7.500, 10.000) = 5164 
    [10.000, 12.500) = 974 
    [12.500, 15.000) = 252 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 70 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.032 ms/op
     p(50.0000) =      4.784 ms/op
     p(90.0000) =      6.275 ms/op
     p(95.0000) =      7.037 ms/op
     p(99.0000) =      9.503 ms/op
     p(99.9000) =     24.365 ms/op
     p(99.9900) =     31.848 ms/op
     p(99.9990) =     33.292 ms/op
     p(99.9999) =     33.292 ms/op
    p(100.0000) =     33.292 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 17.225 ±(99.9%) 0.314 ms/op
# Warmup Iteration   2: 6.005 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.808 ±(99.9%) 0.027 ms/op
Iteration   1: 5.568 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.372 ms/op
                 existUser·p0.50:   5.186 ms/op
                 existUser·p0.90:   7.045 ms/op
                 existUser·p0.95:   8.249 ms/op
                 existUser·p0.99:   11.600 ms/op
                 existUser·p0.999:  17.065 ms/op
                 existUser·p0.9999: 28.320 ms/op
                 existUser·p1.00:   29.065 ms/op

Iteration   2: 5.487 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.817 ms/op
                 existUser·p0.50:   5.145 ms/op
                 existUser·p0.90:   6.857 ms/op
                 existUser·p0.95:   7.971 ms/op
                 existUser·p0.99:   10.535 ms/op
                 existUser·p0.999:  26.753 ms/op
                 existUser·p0.9999: 29.985 ms/op
                 existUser·p1.00:   31.097 ms/op

Iteration   3: 4.922 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.036 ms/op
                 existUser·p0.50:   4.637 ms/op
                 existUser·p0.90:   6.234 ms/op
                 existUser·p0.95:   6.906 ms/op
                 existUser·p0.99:   9.486 ms/op
                 existUser·p0.999:  23.064 ms/op
                 existUser·p0.9999: 32.048 ms/op
                 existUser·p1.00:   33.554 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 180535
  mean =      5.310 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40 
    [ 2.500,  5.000) = 89872 
    [ 5.000,  7.500) = 80201 
    [ 7.500, 10.000) = 7917 
    [10.000, 12.500) = 1786 
    [12.500, 15.000) = 425 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 62 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.817 ms/op
     p(50.0000) =      5.005 ms/op
     p(90.0000) =      6.685 ms/op
     p(95.0000) =      7.733 ms/op
     p(99.0000) =     10.764 ms/op
     p(99.9000) =     17.889 ms/op
     p(99.9900) =     31.454 ms/op
     p(99.9990) =     32.604 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 19.339 ±(99.9%) 0.324 ms/op
# Warmup Iteration   2: 6.768 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.721 ±(99.9%) 0.022 ms/op
Iteration   1: 5.752 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   1.917 ms/op
                 getUser·p0.50:   5.300 ms/op
                 getUser·p0.90:   7.684 ms/op
                 getUser·p0.95:   8.864 ms/op
                 getUser·p0.99:   12.452 ms/op
                 getUser·p0.999:  24.556 ms/op
                 getUser·p0.9999: 28.453 ms/op
                 getUser·p1.00:   29.721 ms/op

Iteration   2: 5.625 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.079 ms/op
                 getUser·p0.50:   5.153 ms/op
                 getUser·p0.90:   7.397 ms/op
                 getUser·p0.95:   8.749 ms/op
                 getUser·p0.99:   11.992 ms/op
                 getUser·p0.999:  27.869 ms/op
                 getUser·p0.9999: 34.996 ms/op
                 getUser·p1.00:   35.324 ms/op

Iteration   3: 5.451 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.847 ms/op
                 getUser·p0.50:   5.087 ms/op
                 getUser·p0.90:   6.963 ms/op
                 getUser·p0.95:   7.963 ms/op
                 getUser·p0.99:   10.289 ms/op
                 getUser·p0.999:  31.172 ms/op
                 getUser·p0.9999: 37.618 ms/op
                 getUser·p1.00:   38.273 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 171215
  mean =      5.606 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 70274 
    [ 5.000,  7.500) = 85322 
    [ 7.500, 10.000) = 11824 
    [10.000, 12.500) = 2604 
    [12.500, 15.000) = 683 
    [15.000, 17.500) = 219 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 44 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.917 ms/op
     p(50.0000) =      5.169 ms/op
     p(90.0000) =      7.332 ms/op
     p(95.0000) =      8.536 ms/op
     p(99.0000) =     11.633 ms/op
     p(99.9000) =     25.749 ms/op
     p(99.9900) =     37.201 ms/op
     p(99.9990) =     37.900 ms/op
     p(99.9999) =     38.273 ms/op
    p(100.0000) =     38.273 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 21.850 ±(99.9%) 0.391 ms/op
# Warmup Iteration   2: 7.639 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 6.197 ±(99.9%) 0.026 ms/op
Iteration   1: 6.526 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.978 ms/op
                 listUser·p0.50:   6.070 ms/op
                 listUser·p0.90:   8.331 ms/op
                 listUser·p0.95:   9.585 ms/op
                 listUser·p0.99:   12.354 ms/op
                 listUser·p0.999:  27.392 ms/op
                 listUser·p0.9999: 32.299 ms/op
                 listUser·p1.00:   34.079 ms/op

Iteration   2: 6.521 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.863 ms/op
                 listUser·p0.50:   6.128 ms/op
                 listUser·p0.90:   8.094 ms/op
                 listUser·p0.95:   9.355 ms/op
                 listUser·p0.99:   12.714 ms/op
                 listUser·p0.999:  29.031 ms/op
                 listUser·p0.9999: 33.102 ms/op
                 listUser·p1.00:   33.686 ms/op

Iteration   3: 6.592 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   3.019 ms/op
                 listUser·p0.50:   6.144 ms/op
                 listUser·p0.90:   8.380 ms/op
                 listUser·p0.95:   9.634 ms/op
                 listUser·p0.99:   12.141 ms/op
                 listUser·p0.999:  27.722 ms/op
                 listUser·p0.9999: 33.106 ms/op
                 listUser·p1.00:   34.537 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 146557
  mean =      6.546 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 6735 
    [ 5.000,  7.500) = 115752 
    [ 7.500, 10.000) = 18615 
    [10.000, 12.500) = 4073 
    [12.500, 15.000) = 859 
    [15.000, 17.500) = 165 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 76 
    [27.500, 30.000) = 84 
    [30.000, 32.500) = 60 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.863 ms/op
     p(50.0000) =      6.119 ms/op
     p(90.0000) =      8.266 ms/op
     p(95.0000) =      9.535 ms/op
     p(99.0000) =     12.370 ms/op
     p(99.9000) =     28.260 ms/op
     p(99.9900) =     33.009 ms/op
     p(99.9990) =     34.324 ms/op
     p(99.9999) =     34.537 ms/op
    p(100.0000) =     34.537 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.239 ± 3.996  ops/ms
ClientPb.existUser                       thrpt       3   5.883 ± 2.009  ops/ms
ClientPb.getUser                         thrpt       3   6.088 ± 2.205  ops/ms
ClientPb.listUser                        thrpt       3   5.698 ± 3.427  ops/ms
ClientPb.createUser                       avgt       3   4.886 ± 0.229   ms/op
ClientPb.existUser                        avgt       3   5.259 ± 0.444   ms/op
ClientPb.getUser                          avgt       3   5.222 ± 2.319   ms/op
ClientPb.listUser                         avgt       3   5.473 ± 3.346   ms/op
ClientPb.createUser                     sample  190437   5.039 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.032           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.784           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.275           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.037           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.503           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.365           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.848           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.292           ms/op
ClientPb.existUser                      sample  180535   5.310 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.817           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.005           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.685           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.733           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.764           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.889           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.454           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.554           ms/op
ClientPb.getUser                        sample  171215   5.606 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.917           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.169           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.332           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.536           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.633           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.749           ms/op
ClientPb.getUser:getUser·p0.9999        sample          37.201           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.273           ms/op
ClientPb.listUser                       sample  146557   6.546 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.863           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.119           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.266           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.535           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.370           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.260           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.009           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.537           ms/op
