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
# Warmup Iteration   1: 1.903 ops/ms
# Warmup Iteration   2: 5.365 ops/ms
# Warmup Iteration   3: 8.880 ops/ms
Iteration   1: 8.977 ops/ms
Iteration   2: 9.498 ops/ms
Iteration   3: 9.356 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.277 ±(99.9%) 4.914 ops/ms [Average]
  (min, avg, max) = (8.977, 9.277, 9.498), stdev = 0.269
  CI (99.9%): [4.363, 14.191] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.091 ops/ms
# Warmup Iteration   2: 8.339 ops/ms
# Warmup Iteration   3: 9.532 ops/ms
Iteration   1: 9.553 ops/ms
Iteration   2: 9.405 ops/ms
Iteration   3: 9.438 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.465 ±(99.9%) 1.411 ops/ms [Average]
  (min, avg, max) = (9.405, 9.465, 9.553), stdev = 0.077
  CI (99.9%): [8.055, 10.876] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.990 ops/ms
# Warmup Iteration   2: 8.466 ops/ms
# Warmup Iteration   3: 8.776 ops/ms
Iteration   1: 9.341 ops/ms
Iteration   2: 9.095 ops/ms
Iteration   3: 9.239 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.225 ±(99.9%) 2.253 ops/ms [Average]
  (min, avg, max) = (9.095, 9.225, 9.341), stdev = 0.124
  CI (99.9%): [6.972, 11.478] (assumes normal distribution)


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
# Warmup Iteration   1: 2.872 ops/ms
# Warmup Iteration   2: 7.448 ops/ms
# Warmup Iteration   3: 8.040 ops/ms
Iteration   1: 8.032 ops/ms
Iteration   2: 8.156 ops/ms
Iteration   3: 8.256 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.148 ±(99.9%) 2.045 ops/ms [Average]
  (min, avg, max) = (8.032, 8.148, 8.256), stdev = 0.112
  CI (99.9%): [6.104, 10.193] (assumes normal distribution)


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
# Warmup Iteration   1: 9.294 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.769 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.694 ±(99.9%) 0.004 ms/op
Iteration   1: 3.482 ±(99.9%) 0.005 ms/op
Iteration   2: 3.366 ±(99.9%) 0.010 ms/op
Iteration   3: 3.350 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.399 ±(99.9%) 1.316 ms/op [Average]
  (min, avg, max) = (3.350, 3.399, 3.482), stdev = 0.072
  CI (99.9%): [2.083, 4.715] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.756 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.539 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.469 ±(99.9%) 0.004 ms/op
Iteration   1: 3.289 ±(99.9%) 0.009 ms/op
Iteration   2: 3.371 ±(99.9%) 0.003 ms/op
Iteration   3: 3.381 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.347 ±(99.9%) 0.919 ms/op [Average]
  (min, avg, max) = (3.289, 3.347, 3.381), stdev = 0.050
  CI (99.9%): [2.428, 4.266] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.912 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.732 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.654 ±(99.9%) 0.009 ms/op
Iteration   1: 3.435 ±(99.9%) 0.012 ms/op
Iteration   2: 3.575 ±(99.9%) 0.005 ms/op
Iteration   3: 3.417 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.476 ±(99.9%) 1.578 ms/op [Average]
  (min, avg, max) = (3.417, 3.476, 3.575), stdev = 0.086
  CI (99.9%): [1.898, 5.054] (assumes normal distribution)


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
# Warmup Iteration   1: 10.393 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.354 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.164 ±(99.9%) 0.011 ms/op
Iteration   1: 3.931 ±(99.9%) 0.013 ms/op
Iteration   2: 3.900 ±(99.9%) 0.010 ms/op
Iteration   3: 4.026 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.952 ±(99.9%) 1.204 ms/op [Average]
  (min, avg, max) = (3.900, 3.952, 4.026), stdev = 0.066
  CI (99.9%): [2.748, 5.157] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.833 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 3.972 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.489 ±(99.9%) 0.010 ms/op
Iteration   1: 3.414 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.841 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.174 ms/op
                 createUser·p0.99:   5.669 ms/op
                 createUser·p0.999:  20.398 ms/op
                 createUser·p0.9999: 22.663 ms/op
                 createUser·p1.00:   23.855 ms/op

Iteration   2: 3.400 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.544 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.080 ms/op
                 createUser·p0.99:   5.718 ms/op
                 createUser·p0.999:  21.559 ms/op
                 createUser·p0.9999: 29.511 ms/op
                 createUser·p1.00:   30.867 ms/op

Iteration   3: 3.362 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.665 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   5.120 ms/op
                 createUser·p0.999:  19.551 ms/op
                 createUser·p0.9999: 27.705 ms/op
                 createUser·p1.00:   28.017 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282997
  mean =      3.392 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7279 
    [ 2.500,  5.000) = 272067 
    [ 5.000,  7.500) = 2703 
    [ 7.500, 10.000) = 500 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 45 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.544 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     19.792 ms/op
     p(99.9900) =     28.344 ms/op
     p(99.9990) =     30.731 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


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
# Warmup Iteration   1: 8.518 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.781 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.487 ±(99.9%) 0.008 ms/op
Iteration   1: 3.252 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.916 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  10.912 ms/op
                 existUser·p0.9999: 22.499 ms/op
                 existUser·p1.00:   22.938 ms/op

Iteration   2: 3.520 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.180 ms/op
                 existUser·p0.50:   3.367 ms/op
                 existUser·p0.90:   4.080 ms/op
                 existUser·p0.95:   4.497 ms/op
                 existUser·p0.99:   6.087 ms/op
                 existUser·p0.999:  21.471 ms/op
                 existUser·p0.9999: 26.107 ms/op
                 existUser·p1.00:   27.689 ms/op

Iteration   3: 3.365 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.427 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.740 ms/op
                 existUser·p0.95:   4.407 ms/op
                 existUser·p0.99:   6.259 ms/op
                 existUser·p0.999:  19.167 ms/op
                 existUser·p0.9999: 27.388 ms/op
                 existUser·p1.00:   28.148 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284525
  mean =      3.375 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4152 
    [ 2.500,  5.000) = 274665 
    [ 5.000,  7.500) = 4598 
    [ 7.500, 10.000) = 688 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 116 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 79 

  Percentiles, ms/op:
      p(0.0000) =      0.916 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      5.915 ms/op
     p(99.9000) =     19.235 ms/op
     p(99.9900) =     26.658 ms/op
     p(99.9990) =     28.060 ms/op
     p(99.9999) =     28.148 ms/op
    p(100.0000) =     28.148 ms/op


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
# Warmup Iteration   1: 11.104 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 3.979 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.610 ±(99.9%) 0.011 ms/op
Iteration   1: 3.597 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.184 ms/op
                 getUser·p0.50:   3.453 ms/op
                 getUser·p0.90:   3.965 ms/op
                 getUser·p0.95:   4.973 ms/op
                 getUser·p0.99:   6.627 ms/op
                 getUser·p0.999:  21.302 ms/op
                 getUser·p0.9999: 23.829 ms/op
                 getUser·p1.00:   25.100 ms/op

Iteration   2: 3.524 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.970 ms/op
                 getUser·p0.50:   3.408 ms/op
                 getUser·p0.90:   4.051 ms/op
                 getUser·p0.95:   4.506 ms/op
                 getUser·p0.99:   5.939 ms/op
                 getUser·p0.999:  23.601 ms/op
                 getUser·p0.9999: 32.045 ms/op
                 getUser·p1.00:   32.440 ms/op

Iteration   3: 3.473 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.819 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   5.865 ms/op
                 getUser·p0.999:  20.207 ms/op
                 getUser·p0.9999: 36.475 ms/op
                 getUser·p1.00:   37.945 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271821
  mean =      3.530 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4364 
    [ 2.500,  5.000) = 257725 
    [ 5.000,  7.500) = 8819 
    [ 7.500, 10.000) = 461 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.184 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      6.218 ms/op
     p(99.9000) =     20.787 ms/op
     p(99.9900) =     35.377 ms/op
     p(99.9990) =     37.261 ms/op
     p(99.9999) =     37.945 ms/op
    p(100.0000) =     37.945 ms/op


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
# Warmup Iteration   1: 12.225 ±(99.9%) 0.180 ms/op
# Warmup Iteration   2: 4.646 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.157 ±(99.9%) 0.014 ms/op
Iteration   1: 4.079 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.915 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   4.981 ms/op
                 listUser·p0.99:   7.635 ms/op
                 listUser·p0.999:  20.939 ms/op
                 listUser·p0.9999: 25.494 ms/op
                 listUser·p1.00:   26.083 ms/op

Iteration   2: 4.137 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.671 ms/op
                 listUser·p0.50:   4.006 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   8.290 ms/op
                 listUser·p0.999:  14.778 ms/op
                 listUser·p0.9999: 21.201 ms/op
                 listUser·p1.00:   21.234 ms/op

Iteration   3: 3.924 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.322 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.006 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   7.528 ms/op
                 listUser·p0.999:  14.402 ms/op
                 listUser·p0.9999: 21.070 ms/op
                 listUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237434
  mean =      4.045 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 68 
    [ 2.500,  5.000) = 227083 
    [ 5.000,  7.500) = 7372 
    [ 7.500, 10.000) = 2103 
    [10.000, 12.500) = 331 
    [12.500, 15.000) = 177 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.915 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      7.870 ms/op
     p(99.9000) =     16.435 ms/op
     p(99.9900) =     23.274 ms/op
     p(99.9990) =     26.038 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.277 ± 4.914  ops/ms
ClientPb.existUser                       thrpt       3   9.465 ± 1.411  ops/ms
ClientPb.getUser                         thrpt       3   9.225 ± 2.253  ops/ms
ClientPb.listUser                        thrpt       3   8.148 ± 2.045  ops/ms
ClientPb.createUser                       avgt       3   3.399 ± 1.316   ms/op
ClientPb.existUser                        avgt       3   3.347 ± 0.919   ms/op
ClientPb.getUser                          avgt       3   3.476 ± 1.578   ms/op
ClientPb.listUser                         avgt       3   3.952 ± 1.204   ms/op
ClientPb.createUser                     sample  282997   3.392 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.544           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.293           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.830           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.080           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.546           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.792           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.344           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.867           ms/op
ClientPb.existUser                      sample  284525   3.375 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.916           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.240           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.801           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.219           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.915           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.235           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.658           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.148           ms/op
ClientPb.getUser                        sample  271821   3.530 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.184           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.404           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.924           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.391           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.218           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.787           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.377           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.945           ms/op
ClientPb.listUser                       sample  237434   4.045 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.915           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.850           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.870           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.435           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.274           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.083           ms/op
