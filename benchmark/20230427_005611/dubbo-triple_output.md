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
# Warmup Iteration   1: 1.220 ops/ms
# Warmup Iteration   2: 2.821 ops/ms
# Warmup Iteration   3: 5.522 ops/ms
Iteration   1: 5.906 ops/ms
Iteration   2: 6.122 ops/ms
Iteration   3: 6.411 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.146 ±(99.9%) 4.615 ops/ms [Average]
  (min, avg, max) = (5.906, 6.146, 6.411), stdev = 0.253
  CI (99.9%): [1.531, 10.762] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 1.585 ops/ms
# Warmup Iteration   2: 4.743 ops/ms
# Warmup Iteration   3: 6.103 ops/ms
Iteration   1: 6.309 ops/ms
Iteration   2: 6.312 ops/ms
Iteration   3: 6.496 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.372 ±(99.9%) 1.954 ops/ms [Average]
  (min, avg, max) = (6.309, 6.372, 6.496), stdev = 0.107
  CI (99.9%): [4.418, 8.326] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.793 ops/ms
# Warmup Iteration   2: 5.405 ops/ms
# Warmup Iteration   3: 6.219 ops/ms
Iteration   1: 6.019 ops/ms
Iteration   2: 6.016 ops/ms
Iteration   3: 6.038 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.024 ±(99.9%) 0.224 ops/ms [Average]
  (min, avg, max) = (6.016, 6.024, 6.038), stdev = 0.012
  CI (99.9%): [5.801, 6.248] (assumes normal distribution)


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
# Warmup Iteration   1: 1.845 ops/ms
# Warmup Iteration   2: 4.718 ops/ms
# Warmup Iteration   3: 5.533 ops/ms
Iteration   1: 5.528 ops/ms
Iteration   2: 5.581 ops/ms
Iteration   3: 5.610 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.573 ±(99.9%) 0.762 ops/ms [Average]
  (min, avg, max) = (5.528, 5.573, 5.610), stdev = 0.042
  CI (99.9%): [4.811, 6.335] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 15.753 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 6.014 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.506 ±(99.9%) 0.009 ms/op
Iteration   1: 5.091 ±(99.9%) 0.018 ms/op
Iteration   2: 4.810 ±(99.9%) 0.013 ms/op
Iteration   3: 5.101 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.000 ±(99.9%) 3.013 ms/op [Average]
  (min, avg, max) = (4.810, 5.000, 5.101), stdev = 0.165
  CI (99.9%): [1.988, 8.013] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 16.294 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 5.805 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.022 ±(99.9%) 0.013 ms/op
Iteration   1: 4.862 ±(99.9%) 0.016 ms/op
Iteration   2: 4.714 ±(99.9%) 0.021 ms/op
Iteration   3: 4.983 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.853 ±(99.9%) 2.458 ms/op [Average]
  (min, avg, max) = (4.714, 4.853, 4.983), stdev = 0.135
  CI (99.9%): [2.395, 7.311] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 17.352 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 6.310 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.430 ±(99.9%) 0.008 ms/op
Iteration   1: 4.923 ±(99.9%) 0.022 ms/op
Iteration   2: 5.094 ±(99.9%) 0.015 ms/op
Iteration   3: 5.091 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.036 ±(99.9%) 1.789 ms/op [Average]
  (min, avg, max) = (4.923, 5.036, 5.094), stdev = 0.098
  CI (99.9%): [3.247, 6.825] (assumes normal distribution)


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
# Warmup Iteration   1: 18.273 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 7.093 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.954 ±(99.9%) 0.017 ms/op
Iteration   1: 6.141 ±(99.9%) 0.013 ms/op
Iteration   2: 6.069 ±(99.9%) 0.013 ms/op
Iteration   3: 6.058 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.089 ±(99.9%) 0.828 ms/op [Average]
  (min, avg, max) = (6.058, 6.089, 6.141), stdev = 0.045
  CI (99.9%): [5.262, 6.917] (assumes normal distribution)


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
# Warmup Iteration   1: 16.591 ±(99.9%) 0.254 ms/op
# Warmup Iteration   2: 6.740 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.541 ±(99.9%) 0.022 ms/op
Iteration   1: 5.082 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.628 ms/op
                 createUser·p0.50:   4.792 ms/op
                 createUser·p0.90:   6.160 ms/op
                 createUser·p0.95:   6.726 ms/op
                 createUser·p0.99:   9.355 ms/op
                 createUser·p0.999:  22.557 ms/op
                 createUser·p0.9999: 28.337 ms/op
                 createUser·p1.00:   28.705 ms/op

Iteration   2: 5.351 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.347 ms/op
                 createUser·p0.50:   5.120 ms/op
                 createUser·p0.90:   6.447 ms/op
                 createUser·p0.95:   7.119 ms/op
                 createUser·p0.99:   9.650 ms/op
                 createUser·p0.999:  23.216 ms/op
                 createUser·p0.9999: 27.329 ms/op
                 createUser·p1.00:   27.722 ms/op

Iteration   3: 5.395 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.388 ms/op
                 createUser·p0.50:   5.251 ms/op
                 createUser·p0.90:   6.439 ms/op
                 createUser·p0.95:   6.906 ms/op
                 createUser·p0.99:   9.025 ms/op
                 createUser·p0.999:  25.887 ms/op
                 createUser·p0.9999: 28.838 ms/op
                 createUser·p1.00:   29.065 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 181893
  mean =      5.272 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 86180 
    [ 5.000,  7.500) = 90107 
    [ 7.500, 10.000) = 4260 
    [10.000, 12.500) = 792 
    [12.500, 15.000) = 203 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 104 

  Percentiles, ms/op:
      p(0.0000) =      1.628 ms/op
     p(50.0000) =      5.054 ms/op
     p(90.0000) =      6.357 ms/op
     p(95.0000) =      6.914 ms/op
     p(99.0000) =      9.355 ms/op
     p(99.9000) =     23.334 ms/op
     p(99.9900) =     28.287 ms/op
     p(99.9990) =     28.985 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


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
# Warmup Iteration   1: 15.534 ±(99.9%) 0.234 ms/op
# Warmup Iteration   2: 5.496 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.235 ±(99.9%) 0.019 ms/op
Iteration   1: 4.955 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.367 ms/op
                 existUser·p0.50:   4.702 ms/op
                 existUser·p0.90:   5.784 ms/op
                 existUser·p0.95:   6.693 ms/op
                 existUser·p0.99:   9.863 ms/op
                 existUser·p0.999:  21.872 ms/op
                 existUser·p0.9999: 29.781 ms/op
                 existUser·p1.00:   38.207 ms/op

Iteration   2: 5.129 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.224 ms/op
                 existUser·p0.50:   4.907 ms/op
                 existUser·p0.90:   6.095 ms/op
                 existUser·p0.95:   6.709 ms/op
                 existUser·p0.99:   9.322 ms/op
                 existUser·p0.999:  27.061 ms/op
                 existUser·p0.9999: 31.769 ms/op
                 existUser·p1.00:   32.309 ms/op

Iteration   3: 4.753 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   2.138 ms/op
                 existUser·p0.50:   4.530 ms/op
                 existUser·p0.90:   5.538 ms/op
                 existUser·p0.95:   6.136 ms/op
                 existUser·p0.99:   8.405 ms/op
                 existUser·p0.999:  14.003 ms/op
                 existUser·p0.9999: 29.533 ms/op
                 existUser·p1.00:   30.147 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 194260
  mean =      4.941 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42 
    [ 2.500,  5.000) = 130894 
    [ 5.000,  7.500) = 57723 
    [ 7.500, 10.000) = 4292 
    [10.000, 12.500) = 919 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 70 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.138 ms/op
     p(50.0000) =      4.694 ms/op
     p(90.0000) =      5.841 ms/op
     p(95.0000) =      6.529 ms/op
     p(99.0000) =      9.322 ms/op
     p(99.9000) =     22.905 ms/op
     p(99.9900) =     31.153 ms/op
     p(99.9990) =     35.551 ms/op
     p(99.9999) =     38.207 ms/op
    p(100.0000) =     38.207 ms/op


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
# Warmup Iteration   1: 14.990 ±(99.9%) 0.235 ms/op
# Warmup Iteration   2: 5.677 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.354 ±(99.9%) 0.018 ms/op
Iteration   1: 5.417 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.062 ms/op
                 getUser·p0.50:   5.161 ms/op
                 getUser·p0.90:   6.357 ms/op
                 getUser·p0.95:   7.455 ms/op
                 getUser·p0.99:   10.953 ms/op
                 getUser·p0.999:  24.372 ms/op
                 getUser·p0.9999: 29.393 ms/op
                 getUser·p1.00:   29.852 ms/op

Iteration   2: 5.298 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.097 ms/op
                 getUser·p0.50:   5.071 ms/op
                 getUser·p0.90:   6.390 ms/op
                 getUser·p0.95:   7.045 ms/op
                 getUser·p0.99:   9.863 ms/op
                 getUser·p0.999:  25.461 ms/op
                 getUser·p0.9999: 30.040 ms/op
                 getUser·p1.00:   31.818 ms/op

Iteration   3: 5.442 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   1.743 ms/op
                 getUser·p0.50:   5.153 ms/op
                 getUser·p0.90:   6.832 ms/op
                 getUser·p0.95:   7.619 ms/op
                 getUser·p0.99:   9.454 ms/op
                 getUser·p0.999:  26.616 ms/op
                 getUser·p0.9999: 59.990 ms/op
                 getUser·p1.00:   63.177 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 178190
  mean =      5.385 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 75757 
    [ 5.000, 10.000) = 100666 
    [10.000, 15.000) = 1273 
    [15.000, 20.000) = 263 
    [20.000, 25.000) = 49 
    [25.000, 30.000) = 144 
    [30.000, 35.000) = 6 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 27 
    [60.000, 65.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.743 ms/op
     p(50.0000) =      5.128 ms/op
     p(90.0000) =      6.488 ms/op
     p(95.0000) =      7.430 ms/op
     p(99.0000) =      9.978 ms/op
     p(99.9000) =     25.395 ms/op
     p(99.9900) =     59.310 ms/op
     p(99.9990) =     62.357 ms/op
     p(99.9999) =     63.177 ms/op
    p(100.0000) =     63.177 ms/op


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
# Warmup Iteration   1: 18.250 ±(99.9%) 0.275 ms/op
# Warmup Iteration   2: 7.236 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 6.208 ±(99.9%) 0.024 ms/op
Iteration   1: 6.088 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.671 ms/op
                 listUser·p0.50:   5.849 ms/op
                 listUser·p0.90:   7.086 ms/op
                 listUser·p0.95:   7.832 ms/op
                 listUser·p0.99:   11.076 ms/op
                 listUser·p0.999:  25.539 ms/op
                 listUser·p0.9999: 29.760 ms/op
                 listUser·p1.00:   29.983 ms/op

Iteration   2: 6.112 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.937 ms/op
                 listUser·p0.50:   5.865 ms/op
                 listUser·p0.90:   7.176 ms/op
                 listUser·p0.95:   8.077 ms/op
                 listUser·p0.99:   10.813 ms/op
                 listUser·p0.999:  26.860 ms/op
                 listUser·p0.9999: 30.048 ms/op
                 listUser·p1.00:   30.736 ms/op

Iteration   3: 5.728 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.769 ms/op
                 listUser·p0.50:   5.489 ms/op
                 listUser·p0.90:   6.636 ms/op
                 listUser·p0.95:   7.340 ms/op
                 listUser·p0.99:   10.273 ms/op
                 listUser·p0.999:  21.305 ms/op
                 listUser·p0.9999: 27.976 ms/op
                 listUser·p1.00:   29.983 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 160732
  mean =      5.971 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 18789 
    [ 5.000,  7.500) = 132204 
    [ 7.500, 10.000) = 7386 
    [10.000, 12.500) = 1443 
    [12.500, 15.000) = 350 
    [15.000, 17.500) = 145 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 105 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.671 ms/op
     p(50.0000) =      5.726 ms/op
     p(90.0000) =      6.988 ms/op
     p(95.0000) =      7.766 ms/op
     p(99.0000) =     10.748 ms/op
     p(99.9000) =     25.397 ms/op
     p(99.9900) =     29.669 ms/op
     p(99.9990) =     30.517 ms/op
     p(99.9999) =     30.736 ms/op
    p(100.0000) =     30.736 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.146 ± 4.615  ops/ms
ClientPb.existUser                       thrpt       3   6.372 ± 1.954  ops/ms
ClientPb.getUser                         thrpt       3   6.024 ± 0.224  ops/ms
ClientPb.listUser                        thrpt       3   5.573 ± 0.762  ops/ms
ClientPb.createUser                       avgt       3   5.000 ± 3.013   ms/op
ClientPb.existUser                        avgt       3   4.853 ± 2.458   ms/op
ClientPb.getUser                          avgt       3   5.036 ± 1.789   ms/op
ClientPb.listUser                         avgt       3   6.089 ± 0.828   ms/op
ClientPb.createUser                     sample  181893   5.272 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.628           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.054           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.357           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.914           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.355           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.334           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.287           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.065           ms/op
ClientPb.existUser                      sample  194260   4.941 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.138           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.694           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.841           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.529           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.322           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.905           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.153           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.207           ms/op
ClientPb.getUser                        sample  178190   5.385 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.743           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.128           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.488           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.430           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.978           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.395           ms/op
ClientPb.getUser:getUser·p0.9999        sample          59.310           ms/op
ClientPb.getUser:getUser·p1.00          sample          63.177           ms/op
ClientPb.listUser                       sample  160732   5.971 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.671           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.726           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.988           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.766           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.748           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.397           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.669           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.736           ms/op
