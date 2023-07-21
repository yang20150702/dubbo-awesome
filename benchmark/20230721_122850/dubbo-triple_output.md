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
# Warmup Iteration   1: 1.081 ops/ms
# Warmup Iteration   2: 2.596 ops/ms
# Warmup Iteration   3: 5.852 ops/ms
Iteration   1: 5.642 ops/ms
Iteration   2: 5.710 ops/ms
Iteration   3: 5.633 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.662 ±(99.9%) 0.773 ops/ms [Average]
  (min, avg, max) = (5.633, 5.662, 5.710), stdev = 0.042
  CI (99.9%): [4.888, 6.435] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.735 ops/ms
# Warmup Iteration   2: 4.994 ops/ms
# Warmup Iteration   3: 6.122 ops/ms
Iteration   1: 6.146 ops/ms
Iteration   2: 6.275 ops/ms
Iteration   3: 6.399 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.273 ±(99.9%) 2.311 ops/ms [Average]
  (min, avg, max) = (6.146, 6.273, 6.399), stdev = 0.127
  CI (99.9%): [3.963, 8.584] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.733 ops/ms
# Warmup Iteration   2: 4.875 ops/ms
# Warmup Iteration   3: 5.932 ops/ms
Iteration   1: 5.773 ops/ms
Iteration   2: 5.753 ops/ms
Iteration   3: 5.873 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.800 ±(99.9%) 1.175 ops/ms [Average]
  (min, avg, max) = (5.753, 5.800, 5.873), stdev = 0.064
  CI (99.9%): [4.624, 6.975] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.467 ops/ms
# Warmup Iteration   2: 4.137 ops/ms
# Warmup Iteration   3: 5.113 ops/ms
Iteration   1: 4.907 ops/ms
Iteration   2: 5.231 ops/ms
Iteration   3: 5.122 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.087 ±(99.9%) 3.005 ops/ms [Average]
  (min, avg, max) = (4.907, 5.087, 5.231), stdev = 0.165
  CI (99.9%): [2.082, 8.092] (assumes normal distribution)


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
# Warmup Iteration   1: 19.200 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 6.716 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.959 ±(99.9%) 0.006 ms/op
Iteration   1: 5.628 ±(99.9%) 0.007 ms/op
Iteration   2: 5.347 ±(99.9%) 0.015 ms/op
Iteration   3: 5.312 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.429 ±(99.9%) 3.156 ms/op [Average]
  (min, avg, max) = (5.312, 5.429, 5.628), stdev = 0.173
  CI (99.9%): [2.274, 8.585] (assumes normal distribution)


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
# Warmup Iteration   1: 15.834 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 6.148 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.399 ±(99.9%) 0.009 ms/op
Iteration   1: 5.327 ±(99.9%) 0.009 ms/op
Iteration   2: 5.251 ±(99.9%) 0.007 ms/op
Iteration   3: 5.220 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.266 ±(99.9%) 1.010 ms/op [Average]
  (min, avg, max) = (5.220, 5.266, 5.327), stdev = 0.055
  CI (99.9%): [4.256, 6.276] (assumes normal distribution)


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
# Warmup Iteration   1: 17.991 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 6.491 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.648 ±(99.9%) 0.015 ms/op
Iteration   1: 5.768 ±(99.9%) 0.007 ms/op
Iteration   2: 5.514 ±(99.9%) 0.012 ms/op
Iteration   3: 5.442 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.575 ±(99.9%) 3.125 ms/op [Average]
  (min, avg, max) = (5.442, 5.575, 5.768), stdev = 0.171
  CI (99.9%): [2.450, 8.700] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 18.570 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 7.756 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.686 ±(99.9%) 0.011 ms/op
Iteration   1: 6.680 ±(99.9%) 0.013 ms/op
Iteration   2: 6.237 ±(99.9%) 0.025 ms/op
Iteration   3: 6.505 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.474 ±(99.9%) 4.070 ms/op [Average]
  (min, avg, max) = (6.237, 6.474, 6.680), stdev = 0.223
  CI (99.9%): [2.404, 10.544] (assumes normal distribution)


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
# Warmup Iteration   1: 18.824 ±(99.9%) 0.328 ms/op
# Warmup Iteration   2: 7.174 ±(99.9%) 0.051 ms/op
# Warmup Iteration   3: 5.862 ±(99.9%) 0.027 ms/op
Iteration   1: 5.508 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   0.824 ms/op
                 createUser·p0.50:   5.153 ms/op
                 createUser·p0.90:   6.955 ms/op
                 createUser·p0.95:   8.086 ms/op
                 createUser·p0.99:   11.076 ms/op
                 createUser·p0.999:  23.390 ms/op
                 createUser·p0.9999: 26.370 ms/op
                 createUser·p1.00:   27.591 ms/op

Iteration   2: 5.420 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.763 ms/op
                 createUser·p0.50:   5.169 ms/op
                 createUser·p0.90:   6.603 ms/op
                 createUser·p0.95:   7.406 ms/op
                 createUser·p0.99:   9.970 ms/op
                 createUser·p0.999:  23.812 ms/op
                 createUser·p0.9999: 28.717 ms/op
                 createUser·p1.00:   29.065 ms/op

Iteration   3: 5.408 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.302 ms/op
                 createUser·p0.50:   5.128 ms/op
                 createUser·p0.90:   6.644 ms/op
                 createUser·p0.95:   7.496 ms/op
                 createUser·p0.99:   9.681 ms/op
                 createUser·p0.999:  26.967 ms/op
                 createUser·p0.9999: 30.838 ms/op
                 createUser·p1.00:   31.130 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 176254
  mean =      5.445 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20 
    [ 2.500,  5.000) = 72808 
    [ 5.000,  7.500) = 93309 
    [ 7.500, 10.000) = 8119 
    [10.000, 12.500) = 1247 
    [12.500, 15.000) = 417 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 66 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      5.153 ms/op
     p(90.0000) =      6.717 ms/op
     p(95.0000) =      7.717 ms/op
     p(99.0000) =     10.240 ms/op
     p(99.9000) =     23.666 ms/op
     p(99.9900) =     29.819 ms/op
     p(99.9990) =     31.105 ms/op
     p(99.9999) =     31.130 ms/op
    p(100.0000) =     31.130 ms/op


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
# Warmup Iteration   1: 16.219 ±(99.9%) 0.285 ms/op
# Warmup Iteration   2: 6.894 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 5.415 ±(99.9%) 0.021 ms/op
Iteration   1: 5.523 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.523 ms/op
                 existUser·p0.50:   5.136 ms/op
                 existUser·p0.90:   7.135 ms/op
                 existUser·p0.95:   8.552 ms/op
                 existUser·p0.99:   11.452 ms/op
                 existUser·p0.999:  16.876 ms/op
                 existUser·p0.9999: 33.528 ms/op
                 existUser·p1.00:   34.537 ms/op

Iteration   2: 5.253 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.548 ms/op
                 existUser·p0.50:   4.981 ms/op
                 existUser·p0.90:   6.537 ms/op
                 existUser·p0.95:   7.447 ms/op
                 existUser·p0.99:   10.043 ms/op
                 existUser·p0.999:  26.015 ms/op
                 existUser·p0.9999: 30.512 ms/op
                 existUser·p1.00:   31.162 ms/op

Iteration   3: 5.369 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.506 ms/op
                 existUser·p0.50:   5.046 ms/op
                 existUser·p0.90:   6.742 ms/op
                 existUser·p0.95:   7.692 ms/op
                 existUser·p0.99:   10.945 ms/op
                 existUser·p0.999:  28.344 ms/op
                 existUser·p0.9999: 37.232 ms/op
                 existUser·p1.00:   37.880 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 178375
  mean =      5.379 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 83416 
    [ 5.000,  7.500) = 83582 
    [ 7.500, 10.000) = 8653 
    [10.000, 12.500) = 2017 
    [12.500, 15.000) = 436 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 40 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.506 ms/op
     p(50.0000) =      5.046 ms/op
     p(90.0000) =      6.775 ms/op
     p(95.0000) =      7.938 ms/op
     p(99.0000) =     10.863 ms/op
     p(99.9000) =     17.531 ms/op
     p(99.9900) =     33.772 ms/op
     p(99.9990) =     37.828 ms/op
     p(99.9999) =     37.880 ms/op
    p(100.0000) =     37.880 ms/op


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
# Warmup Iteration   1: 17.061 ±(99.9%) 0.300 ms/op
# Warmup Iteration   2: 6.504 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.604 ±(99.9%) 0.023 ms/op
Iteration   1: 5.641 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   2.359 ms/op
                 getUser·p0.50:   5.186 ms/op
                 getUser·p0.90:   7.274 ms/op
                 getUser·p0.95:   8.945 ms/op
                 getUser·p0.99:   13.255 ms/op
                 getUser·p0.999:  24.160 ms/op
                 getUser·p0.9999: 34.603 ms/op
                 getUser·p1.00:   34.931 ms/op

Iteration   2: 5.322 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.535 ms/op
                 getUser·p0.50:   4.997 ms/op
                 getUser·p0.90:   6.537 ms/op
                 getUser·p0.95:   7.651 ms/op
                 getUser·p0.99:   10.895 ms/op
                 getUser·p0.999:  25.330 ms/op
                 getUser·p0.9999: 29.949 ms/op
                 getUser·p1.00:   30.409 ms/op

Iteration   3: 5.260 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.281 ms/op
                 getUser·p0.50:   4.981 ms/op
                 getUser·p0.90:   6.382 ms/op
                 getUser·p0.95:   7.193 ms/op
                 getUser·p0.99:   10.080 ms/op
                 getUser·p0.999:  26.979 ms/op
                 getUser·p0.9999: 32.002 ms/op
                 getUser·p1.00:   35.258 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 177568
  mean =      5.403 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 84549 
    [ 5.000,  7.500) = 82177 
    [ 7.500, 10.000) = 7479 
    [10.000, 12.500) = 2059 
    [12.500, 15.000) = 811 
    [15.000, 17.500) = 249 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.281 ms/op
     p(50.0000) =      5.038 ms/op
     p(90.0000) =      6.676 ms/op
     p(95.0000) =      7.905 ms/op
     p(99.0000) =     11.305 ms/op
     p(99.9000) =     25.008 ms/op
     p(99.9900) =     33.292 ms/op
     p(99.9990) =     35.004 ms/op
     p(99.9999) =     35.258 ms/op
    p(100.0000) =     35.258 ms/op


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
# Warmup Iteration   1: 19.265 ±(99.9%) 0.319 ms/op
# Warmup Iteration   2: 7.824 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 6.331 ±(99.9%) 0.027 ms/op
Iteration   1: 6.074 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.863 ms/op
                 listUser·p0.50:   5.734 ms/op
                 listUser·p0.90:   7.471 ms/op
                 listUser·p0.95:   8.520 ms/op
                 listUser·p0.99:   11.338 ms/op
                 listUser·p0.999:  26.903 ms/op
                 listUser·p0.9999: 29.957 ms/op
                 listUser·p1.00:   30.638 ms/op

Iteration   2: 6.019 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   3.019 ms/op
                 listUser·p0.50:   5.636 ms/op
                 listUser·p0.90:   7.422 ms/op
                 listUser·p0.95:   8.233 ms/op
                 listUser·p0.99:   11.239 ms/op
                 listUser·p0.999:  34.210 ms/op
                 listUser·p0.9999: 36.090 ms/op
                 listUser·p1.00:   38.076 ms/op

Iteration   3: 6.283 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.606 ms/op
                 listUser·p0.50:   5.865 ms/op
                 listUser·p0.90:   7.979 ms/op
                 listUser·p0.95:   9.273 ms/op
                 listUser·p0.99:   12.370 ms/op
                 listUser·p0.999:  23.006 ms/op
                 listUser·p0.9999: 27.489 ms/op
                 listUser·p1.00:   28.115 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 156711
  mean =      6.124 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 18042 
    [ 5.000,  7.500) = 121798 
    [ 7.500, 10.000) = 13184 
    [10.000, 12.500) = 2610 
    [12.500, 15.000) = 643 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 97 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 40 
    [35.000, 37.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.606 ms/op
     p(50.0000) =      5.751 ms/op
     p(90.0000) =      7.602 ms/op
     p(95.0000) =      8.651 ms/op
     p(99.0000) =     11.747 ms/op
     p(99.9000) =     26.935 ms/op
     p(99.9900) =     35.389 ms/op
     p(99.9990) =     37.630 ms/op
     p(99.9999) =     38.076 ms/op
    p(100.0000) =     38.076 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.662 ± 0.773  ops/ms
ClientPb.existUser                       thrpt       3   6.273 ± 2.311  ops/ms
ClientPb.getUser                         thrpt       3   5.800 ± 1.175  ops/ms
ClientPb.listUser                        thrpt       3   5.087 ± 3.005  ops/ms
ClientPb.createUser                       avgt       3   5.429 ± 3.156   ms/op
ClientPb.existUser                        avgt       3   5.266 ± 1.010   ms/op
ClientPb.getUser                          avgt       3   5.575 ± 3.125   ms/op
ClientPb.listUser                         avgt       3   6.474 ± 4.070   ms/op
ClientPb.createUser                     sample  176254   5.445 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.824           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.153           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.717           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.717           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.240           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.666           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.819           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.130           ms/op
ClientPb.existUser                      sample  178375   5.379 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.506           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.046           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.775           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.938           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.863           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.531           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.772           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.880           ms/op
ClientPb.getUser                        sample  177568   5.403 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.281           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.038           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.676           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.905           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.305           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.008           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.292           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.258           ms/op
ClientPb.listUser                       sample  156711   6.124 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.606           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.751           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.602           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.651           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.747           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.935           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.389           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.076           ms/op
