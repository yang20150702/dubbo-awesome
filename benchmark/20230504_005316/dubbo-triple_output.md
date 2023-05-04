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
# Warmup Iteration   1: 1.893 ops/ms
# Warmup Iteration   2: 5.592 ops/ms
# Warmup Iteration   3: 8.806 ops/ms
Iteration   1: 9.217 ops/ms
Iteration   2: 9.457 ops/ms
Iteration   3: 9.172 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.282 ±(99.9%) 2.793 ops/ms [Average]
  (min, avg, max) = (9.172, 9.282, 9.457), stdev = 0.153
  CI (99.9%): [6.489, 12.075] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.094 ops/ms
# Warmup Iteration   2: 7.900 ops/ms
# Warmup Iteration   3: 9.185 ops/ms
Iteration   1: 9.805 ops/ms
Iteration   2: 10.155 ops/ms
Iteration   3: 10.091 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.017 ±(99.9%) 3.406 ops/ms [Average]
  (min, avg, max) = (9.805, 10.017, 10.155), stdev = 0.187
  CI (99.9%): [6.611, 13.424] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.038 ops/ms
# Warmup Iteration   2: 8.521 ops/ms
# Warmup Iteration   3: 9.135 ops/ms
Iteration   1: 9.269 ops/ms
Iteration   2: 9.393 ops/ms
Iteration   3: 9.167 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.276 ±(99.9%) 2.072 ops/ms [Average]
  (min, avg, max) = (9.167, 9.276, 9.393), stdev = 0.114
  CI (99.9%): [7.204, 11.349] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.691 ops/ms
# Warmup Iteration   2: 6.953 ops/ms
# Warmup Iteration   3: 7.827 ops/ms
Iteration   1: 8.063 ops/ms
Iteration   2: 7.803 ops/ms
Iteration   3: 7.972 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.946 ±(99.9%) 2.401 ops/ms [Average]
  (min, avg, max) = (7.803, 7.946, 8.063), stdev = 0.132
  CI (99.9%): [5.545, 10.348] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.468 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.970 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.613 ±(99.9%) 0.008 ms/op
Iteration   1: 3.399 ±(99.9%) 0.006 ms/op
Iteration   2: 3.428 ±(99.9%) 0.007 ms/op
Iteration   3: 3.540 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.456 ±(99.9%) 1.363 ms/op [Average]
  (min, avg, max) = (3.399, 3.456, 3.540), stdev = 0.075
  CI (99.9%): [2.092, 4.819] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 10.438 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.564 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.251 ±(99.9%) 0.006 ms/op
Iteration   1: 3.263 ±(99.9%) 0.003 ms/op
Iteration   2: 3.233 ±(99.9%) 0.009 ms/op
Iteration   3: 3.314 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.270 ±(99.9%) 0.754 ms/op [Average]
  (min, avg, max) = (3.233, 3.270, 3.314), stdev = 0.041
  CI (99.9%): [2.516, 4.024] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.910 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.705 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.638 ±(99.9%) 0.005 ms/op
Iteration   1: 3.444 ±(99.9%) 0.008 ms/op
Iteration   2: 3.382 ±(99.9%) 0.006 ms/op
Iteration   3: 3.349 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.391 ±(99.9%) 0.880 ms/op [Average]
  (min, avg, max) = (3.349, 3.391, 3.444), stdev = 0.048
  CI (99.9%): [2.511, 4.271] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.693 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.542 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.164 ±(99.9%) 0.010 ms/op
Iteration   1: 3.990 ±(99.9%) 0.010 ms/op
Iteration   2: 4.022 ±(99.9%) 0.006 ms/op
Iteration   3: 3.898 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.970 ±(99.9%) 1.169 ms/op [Average]
  (min, avg, max) = (3.898, 3.970, 4.022), stdev = 0.064
  CI (99.9%): [2.801, 5.139] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.660 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 4.017 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.878 ±(99.9%) 0.014 ms/op
Iteration   1: 3.405 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.169 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   4.055 ms/op
                 createUser·p0.99:   6.496 ms/op
                 createUser·p0.999:  20.314 ms/op
                 createUser·p0.9999: 29.164 ms/op
                 createUser·p1.00:   34.013 ms/op

Iteration   2: 3.392 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.432 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   4.170 ms/op
                 createUser·p0.99:   5.890 ms/op
                 createUser·p0.999:  22.561 ms/op
                 createUser·p0.9999: 26.069 ms/op
                 createUser·p1.00:   27.230 ms/op

Iteration   3: 3.378 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.419 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   5.865 ms/op
                 createUser·p0.999:  20.000 ms/op
                 createUser·p0.9999: 27.870 ms/op
                 createUser·p1.00:   28.475 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282974
  mean =      3.392 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9930 
    [ 2.500,  5.000) = 267031 
    [ 5.000,  7.500) = 4859 
    [ 7.500, 10.000) = 617 
    [10.000, 12.500) = 215 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 76 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.084 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     20.188 ms/op
     p(99.9900) =     28.105 ms/op
     p(99.9990) =     29.901 ms/op
     p(99.9999) =     34.013 ms/op
    p(100.0000) =     34.013 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.220 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.698 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.361 ±(99.9%) 0.010 ms/op
Iteration   1: 3.303 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.311 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.858 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  9.273 ms/op
                 existUser·p0.9999: 22.260 ms/op
                 existUser·p1.00:   25.985 ms/op

Iteration   2: 3.278 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.337 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   5.374 ms/op
                 existUser·p0.999:  11.001 ms/op
                 existUser·p0.9999: 25.919 ms/op
                 existUser·p1.00:   26.739 ms/op

Iteration   3: 3.382 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.688 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.703 ms/op
                 existUser·p0.95:   4.104 ms/op
                 existUser·p0.99:   6.726 ms/op
                 existUser·p0.999:  19.341 ms/op
                 existUser·p0.9999: 25.555 ms/op
                 existUser·p1.00:   26.247 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288979
  mean =      3.321 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6004 
    [ 2.500,  5.000) = 277068 
    [ 5.000,  7.500) = 4987 
    [ 7.500, 10.000) = 531 
    [10.000, 12.500) = 131 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 106 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 52 

  Percentiles, ms/op:
      p(0.0000) =      1.311 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      5.775 ms/op
     p(99.9000) =     11.190 ms/op
     p(99.9900) =     25.661 ms/op
     p(99.9990) =     26.611 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.701 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.906 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.598 ±(99.9%) 0.011 ms/op
Iteration   1: 3.481 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.978 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.432 ms/op
                 getUser·p0.99:   6.693 ms/op
                 getUser·p0.999:  21.135 ms/op
                 getUser·p0.9999: 23.554 ms/op
                 getUser·p1.00:   25.297 ms/op

Iteration   2: 3.367 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.708 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   3.981 ms/op
                 getUser·p0.99:   5.800 ms/op
                 getUser·p0.999:  22.797 ms/op
                 getUser·p0.9999: 25.428 ms/op
                 getUser·p1.00:   26.280 ms/op

Iteration   3: 3.598 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.348 ms/op
                 getUser·p0.50:   3.449 ms/op
                 getUser·p0.90:   4.194 ms/op
                 getUser·p0.95:   4.538 ms/op
                 getUser·p0.99:   6.406 ms/op
                 getUser·p0.999:  21.332 ms/op
                 getUser·p0.9999: 30.653 ms/op
                 getUser·p1.00:   31.752 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275794
  mean =      3.480 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8177 
    [ 2.500,  5.000) = 259715 
    [ 5.000,  7.500) = 6568 
    [ 7.500, 10.000) = 692 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 125 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.348 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      6.398 ms/op
     p(99.9000) =     21.332 ms/op
     p(99.9900) =     30.122 ms/op
     p(99.9990) =     31.719 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.275 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.719 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.206 ±(99.9%) 0.013 ms/op
Iteration   1: 4.219 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.391 ms/op
                 listUser·p0.50:   4.002 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   7.972 ms/op
                 listUser·p0.999:  20.164 ms/op
                 listUser·p0.9999: 26.662 ms/op
                 listUser·p1.00:   29.196 ms/op

Iteration   2: 4.107 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.335 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   7.930 ms/op
                 listUser·p0.999:  16.138 ms/op
                 listUser·p0.9999: 21.241 ms/op
                 listUser·p1.00:   22.512 ms/op

Iteration   3: 4.008 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.327 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  15.091 ms/op
                 listUser·p0.9999: 24.117 ms/op
                 listUser·p1.00:   24.150 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 233659
  mean =      4.109 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 221988 
    [ 5.000,  7.500) = 9055 
    [ 7.500, 10.000) = 1572 
    [10.000, 12.500) = 417 
    [12.500, 15.000) = 183 
    [15.000, 17.500) = 198 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.391 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      7.646 ms/op
     p(99.9000) =     16.712 ms/op
     p(99.9900) =     25.502 ms/op
     p(99.9990) =     27.219 ms/op
     p(99.9999) =     29.196 ms/op
    p(100.0000) =     29.196 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.282 ± 2.793  ops/ms
ClientPb.existUser                       thrpt       3  10.017 ± 3.406  ops/ms
ClientPb.getUser                         thrpt       3   9.276 ± 2.072  ops/ms
ClientPb.listUser                        thrpt       3   7.946 ± 2.401  ops/ms
ClientPb.createUser                       avgt       3   3.456 ± 1.363   ms/op
ClientPb.existUser                        avgt       3   3.270 ± 0.754   ms/op
ClientPb.getUser                          avgt       3   3.391 ± 0.880   ms/op
ClientPb.listUser                         avgt       3   3.970 ± 1.169   ms/op
ClientPb.createUser                     sample  282974   3.392 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.169           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.289           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.752           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.084           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.972           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.188           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.105           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.013           ms/op
ClientPb.existUser                      sample  288979   3.321 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.311           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.203           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.654           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.924           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.775           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.190           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.661           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.739           ms/op
ClientPb.getUser                        sample  275794   3.480 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.348           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.334           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.977           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.358           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.398           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.332           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.122           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.752           ms/op
ClientPb.listUser                       sample  233659   4.109 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.391           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.928           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.997           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.646           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.712           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.502           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.196           ms/op
