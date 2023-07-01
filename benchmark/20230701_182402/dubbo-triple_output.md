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
# Warmup Iteration   1: 1.097 ops/ms
# Warmup Iteration   2: 2.526 ops/ms
# Warmup Iteration   3: 5.349 ops/ms
Iteration   1: 5.604 ops/ms
Iteration   2: 5.720 ops/ms
Iteration   3: 5.802 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.708 ±(99.9%) 1.820 ops/ms [Average]
  (min, avg, max) = (5.604, 5.708, 5.802), stdev = 0.100
  CI (99.9%): [3.888, 7.529] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.530 ops/ms
# Warmup Iteration   2: 4.464 ops/ms
# Warmup Iteration   3: 5.995 ops/ms
Iteration   1: 6.132 ops/ms
Iteration   2: 5.954 ops/ms
Iteration   3: 6.178 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.088 ±(99.9%) 2.161 ops/ms [Average]
  (min, avg, max) = (5.954, 6.088, 6.178), stdev = 0.118
  CI (99.9%): [3.927, 8.249] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.784 ops/ms
# Warmup Iteration   2: 4.987 ops/ms
# Warmup Iteration   3: 5.724 ops/ms
Iteration   1: 5.696 ops/ms
Iteration   2: 5.563 ops/ms
Iteration   3: 5.797 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.686 ±(99.9%) 2.141 ops/ms [Average]
  (min, avg, max) = (5.563, 5.686, 5.797), stdev = 0.117
  CI (99.9%): [3.545, 7.826] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.574 ops/ms
# Warmup Iteration   2: 4.134 ops/ms
# Warmup Iteration   3: 4.882 ops/ms
Iteration   1: 4.861 ops/ms
Iteration   2: 5.014 ops/ms
Iteration   3: 4.964 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.947 ±(99.9%) 1.428 ops/ms [Average]
  (min, avg, max) = (4.861, 4.947, 5.014), stdev = 0.078
  CI (99.9%): [3.518, 6.375] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 17.611 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 7.330 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.903 ±(99.9%) 0.013 ms/op
Iteration   1: 5.488 ±(99.9%) 0.019 ms/op
Iteration   2: 5.849 ±(99.9%) 0.011 ms/op
Iteration   3: 5.349 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.562 ±(99.9%) 4.709 ms/op [Average]
  (min, avg, max) = (5.349, 5.562, 5.849), stdev = 0.258
  CI (99.9%): [0.853, 10.271] (assumes normal distribution)


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
# Warmup Iteration   1: 17.267 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 6.272 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.336 ±(99.9%) 0.011 ms/op
Iteration   1: 5.326 ±(99.9%) 0.009 ms/op
Iteration   2: 5.132 ±(99.9%) 0.013 ms/op
Iteration   3: 5.270 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.243 ±(99.9%) 1.827 ms/op [Average]
  (min, avg, max) = (5.132, 5.243, 5.326), stdev = 0.100
  CI (99.9%): [3.415, 7.070] (assumes normal distribution)


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
# Warmup Iteration   1: 18.198 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 6.442 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.590 ±(99.9%) 0.014 ms/op
Iteration   1: 5.526 ±(99.9%) 0.011 ms/op
Iteration   2: 5.652 ±(99.9%) 0.014 ms/op
Iteration   3: 5.498 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.559 ±(99.9%) 1.501 ms/op [Average]
  (min, avg, max) = (5.498, 5.559, 5.652), stdev = 0.082
  CI (99.9%): [4.058, 7.059] (assumes normal distribution)


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
# Warmup Iteration   1: 20.156 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 7.411 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.601 ±(99.9%) 0.018 ms/op
Iteration   1: 6.588 ±(99.9%) 0.016 ms/op
Iteration   2: 6.371 ±(99.9%) 0.019 ms/op
Iteration   3: 6.420 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.460 ±(99.9%) 2.076 ms/op [Average]
  (min, avg, max) = (6.371, 6.460, 6.588), stdev = 0.114
  CI (99.9%): [4.383, 8.536] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 17.479 ±(99.9%) 0.276 ms/op
# Warmup Iteration   2: 7.354 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 6.185 ±(99.9%) 0.029 ms/op
Iteration   1: 5.484 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.228 ms/op
                 createUser·p0.50:   5.243 ms/op
                 createUser·p0.90:   6.619 ms/op
                 createUser·p0.95:   7.406 ms/op
                 createUser·p0.99:   10.306 ms/op
                 createUser·p0.999:  23.560 ms/op
                 createUser·p0.9999: 30.059 ms/op
                 createUser·p1.00:   30.474 ms/op

Iteration   2: 5.385 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.585 ms/op
                 createUser·p0.50:   5.136 ms/op
                 createUser·p0.90:   6.521 ms/op
                 createUser·p0.95:   7.438 ms/op
                 createUser·p0.99:   9.570 ms/op
                 createUser·p0.999:  26.432 ms/op
                 createUser·p0.9999: 30.091 ms/op
                 createUser·p1.00:   31.031 ms/op

Iteration   3: 5.553 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.042 ms/op
                 createUser·p0.50:   5.259 ms/op
                 createUser·p0.90:   6.783 ms/op
                 createUser·p0.95:   7.832 ms/op
                 createUser·p0.99:   10.437 ms/op
                 createUser·p0.999:  28.705 ms/op
                 createUser·p0.9999: 32.464 ms/op
                 createUser·p1.00:   32.997 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 175285
  mean =      5.473 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 66053 
    [ 5.000,  7.500) = 100216 
    [ 7.500, 10.000) = 7206 
    [10.000, 12.500) = 1145 
    [12.500, 15.000) = 341 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 100 
    [30.000, 32.500) = 48 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.042 ms/op
     p(50.0000) =      5.210 ms/op
     p(90.0000) =      6.644 ms/op
     p(95.0000) =      7.553 ms/op
     p(99.0000) =     10.043 ms/op
     p(99.9000) =     24.576 ms/op
     p(99.9900) =     30.931 ms/op
     p(99.9990) =     32.948 ms/op
     p(99.9999) =     32.997 ms/op
    p(100.0000) =     32.997 ms/op


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
# Warmup Iteration   1: 17.488 ±(99.9%) 0.291 ms/op
# Warmup Iteration   2: 7.168 ±(99.9%) 0.051 ms/op
# Warmup Iteration   3: 5.610 ±(99.9%) 0.022 ms/op
Iteration   1: 5.448 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.417 ms/op
                 existUser·p0.50:   5.136 ms/op
                 existUser·p0.90:   6.734 ms/op
                 existUser·p0.95:   7.758 ms/op
                 existUser·p0.99:   10.011 ms/op
                 existUser·p0.999:  23.858 ms/op
                 existUser·p0.9999: 29.442 ms/op
                 existUser·p1.00:   30.278 ms/op

Iteration   2: 5.455 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.421 ms/op
                 existUser·p0.50:   5.136 ms/op
                 existUser·p0.90:   6.832 ms/op
                 existUser·p0.95:   7.643 ms/op
                 existUser·p0.99:   9.798 ms/op
                 existUser·p0.999:  15.516 ms/op
                 existUser·p0.9999: 34.695 ms/op
                 existUser·p1.00:   35.062 ms/op

Iteration   3: 5.361 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.277 ms/op
                 existUser·p0.50:   5.054 ms/op
                 existUser·p0.90:   6.791 ms/op
                 existUser·p0.95:   7.660 ms/op
                 existUser·p0.99:   9.978 ms/op
                 existUser·p0.999:  27.273 ms/op
                 existUser·p0.9999: 38.404 ms/op
                 existUser·p1.00:   38.994 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 176989
  mean =      5.421 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 75759 
    [ 5.000,  7.500) = 91155 
    [ 7.500, 10.000) = 8379 
    [10.000, 12.500) = 1184 
    [12.500, 15.000) = 259 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      2.277 ms/op
     p(50.0000) =      5.104 ms/op
     p(90.0000) =      6.791 ms/op
     p(95.0000) =      7.692 ms/op
     p(99.0000) =      9.880 ms/op
     p(99.9000) =     17.957 ms/op
     p(99.9900) =     35.442 ms/op
     p(99.9990) =     38.792 ms/op
     p(99.9999) =     38.994 ms/op
    p(100.0000) =     38.994 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 17.977 ±(99.9%) 0.314 ms/op
# Warmup Iteration   2: 6.478 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.641 ±(99.9%) 0.021 ms/op
Iteration   1: 5.747 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   2.826 ms/op
                 getUser·p0.50:   5.218 ms/op
                 getUser·p0.90:   7.627 ms/op
                 getUser·p0.95:   9.159 ms/op
                 getUser·p0.99:   13.560 ms/op
                 getUser·p0.999:  25.595 ms/op
                 getUser·p0.9999: 30.210 ms/op
                 getUser·p1.00:   31.031 ms/op

Iteration   2: 5.519 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.650 ms/op
                 getUser·p0.50:   5.153 ms/op
                 getUser·p0.90:   6.824 ms/op
                 getUser·p0.95:   8.315 ms/op
                 getUser·p0.99:   11.551 ms/op
                 getUser·p0.999:  29.524 ms/op
                 getUser·p0.9999: 32.742 ms/op
                 getUser·p1.00:   34.734 ms/op

Iteration   3: 5.520 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.527 ms/op
                 getUser·p0.50:   5.194 ms/op
                 getUser·p0.90:   6.791 ms/op
                 getUser·p0.95:   7.946 ms/op
                 getUser·p0.99:   10.489 ms/op
                 getUser·p0.999:  27.918 ms/op
                 getUser·p0.9999: 31.347 ms/op
                 getUser·p1.00:   31.982 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 171510
  mean =      5.593 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 63949 
    [ 5.000,  7.500) = 94224 
    [ 7.500, 10.000) = 9248 
    [10.000, 12.500) = 2696 
    [12.500, 15.000) = 696 
    [15.000, 17.500) = 388 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 86 
    [30.000, 32.500) = 64 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.527 ms/op
     p(50.0000) =      5.186 ms/op
     p(90.0000) =      7.021 ms/op
     p(95.0000) =      8.487 ms/op
     p(99.0000) =     12.059 ms/op
     p(99.9000) =     27.001 ms/op
     p(99.9900) =     31.944 ms/op
     p(99.9990) =     34.078 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


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
# Warmup Iteration   1: 20.243 ±(99.9%) 0.339 ms/op
# Warmup Iteration   2: 7.972 ±(99.9%) 0.051 ms/op
# Warmup Iteration   3: 6.569 ±(99.9%) 0.027 ms/op
Iteration   1: 6.613 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.663 ms/op
                 listUser·p0.50:   6.291 ms/op
                 listUser·p0.90:   7.913 ms/op
                 listUser·p0.95:   9.339 ms/op
                 listUser·p0.99:   12.517 ms/op
                 listUser·p0.999:  26.628 ms/op
                 listUser·p0.9999: 30.099 ms/op
                 listUser·p1.00:   32.571 ms/op

Iteration   2: 6.374 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   3.240 ms/op
                 listUser·p0.50:   6.029 ms/op
                 listUser·p0.90:   7.635 ms/op
                 listUser·p0.95:   8.880 ms/op
                 listUser·p0.99:   11.715 ms/op
                 listUser·p0.999:  29.649 ms/op
                 listUser·p0.9999: 32.308 ms/op
                 listUser·p1.00:   34.800 ms/op

Iteration   3: 6.329 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.763 ms/op
                 listUser·p0.50:   5.980 ms/op
                 listUser·p0.90:   7.569 ms/op
                 listUser·p0.95:   8.585 ms/op
                 listUser·p0.99:   11.895 ms/op
                 listUser·p0.999:  23.804 ms/op
                 listUser·p0.9999: 27.818 ms/op
                 listUser·p1.00:   28.017 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 149114
  mean =      6.436 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 5306 
    [ 5.000,  7.500) = 126392 
    [ 7.500, 10.000) = 13156 
    [10.000, 12.500) = 3014 
    [12.500, 15.000) = 731 
    [15.000, 17.500) = 180 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 85 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.663 ms/op
     p(50.0000) =      6.087 ms/op
     p(90.0000) =      7.700 ms/op
     p(95.0000) =      8.897 ms/op
     p(99.0000) =     12.075 ms/op
     p(99.9000) =     27.066 ms/op
     p(99.9900) =     32.050 ms/op
     p(99.9990) =     33.705 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


# Run complete. Total time: 00:13:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.708 ± 1.820  ops/ms
ClientPb.existUser                       thrpt       3   6.088 ± 2.161  ops/ms
ClientPb.getUser                         thrpt       3   5.686 ± 2.141  ops/ms
ClientPb.listUser                        thrpt       3   4.947 ± 1.428  ops/ms
ClientPb.createUser                       avgt       3   5.562 ± 4.709   ms/op
ClientPb.existUser                        avgt       3   5.243 ± 1.827   ms/op
ClientPb.getUser                          avgt       3   5.559 ± 1.501   ms/op
ClientPb.listUser                         avgt       3   6.460 ± 2.076   ms/op
ClientPb.createUser                     sample  175285   5.473 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.042           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.210           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.644           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.553           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.043           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.576           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.931           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.997           ms/op
ClientPb.existUser                      sample  176989   5.421 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.277           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.104           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.791           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.692           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.880           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.957           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.442           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.994           ms/op
ClientPb.getUser                        sample  171510   5.593 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.527           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.186           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.021           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.487           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.059           ms/op
ClientPb.getUser:getUser·p0.999         sample          27.001           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.944           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.734           ms/op
ClientPb.listUser                       sample  149114   6.436 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.663           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.087           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.700           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.897           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.075           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.066           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.050           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.800           ms/op
