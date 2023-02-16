# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.215 ops/ms
# Warmup Iteration   2: 2.906 ops/ms
# Warmup Iteration   3: 5.792 ops/ms
Iteration   1: 5.881 ops/ms
Iteration   2: 6.060 ops/ms
Iteration   3: 6.100 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.014 ±(99.9%) 2.124 ops/ms [Average]
  (min, avg, max) = (5.881, 6.014, 6.100), stdev = 0.116
  CI (99.9%): [3.890, 8.138] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.747 ops/ms
# Warmup Iteration   2: 5.266 ops/ms
# Warmup Iteration   3: 6.279 ops/ms
Iteration   1: 6.448 ops/ms
Iteration   2: 6.609 ops/ms
Iteration   3: 6.494 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.517 ±(99.9%) 1.518 ops/ms [Average]
  (min, avg, max) = (6.448, 6.517, 6.609), stdev = 0.083
  CI (99.9%): [4.999, 8.035] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.649 ops/ms
# Warmup Iteration   2: 4.569 ops/ms
# Warmup Iteration   3: 5.802 ops/ms
Iteration   1: 6.379 ops/ms
Iteration   2: 6.153 ops/ms
Iteration   3: 6.399 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.311 ±(99.9%) 2.488 ops/ms [Average]
  (min, avg, max) = (6.153, 6.311, 6.399), stdev = 0.136
  CI (99.9%): [3.822, 8.799] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.789 ops/ms
# Warmup Iteration   2: 4.484 ops/ms
# Warmup Iteration   3: 5.307 ops/ms
Iteration   1: 5.275 ops/ms
Iteration   2: 5.292 ops/ms
Iteration   3: 5.453 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.340 ±(99.9%) 1.795 ops/ms [Average]
  (min, avg, max) = (5.275, 5.340, 5.453), stdev = 0.098
  CI (99.9%): [3.546, 7.135] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 16.119 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 6.129 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.202 ±(99.9%) 0.011 ms/op
Iteration   1: 5.089 ±(99.9%) 0.011 ms/op
Iteration   2: 5.120 ±(99.9%) 0.013 ms/op
Iteration   3: 5.005 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.071 ±(99.9%) 1.086 ms/op [Average]
  (min, avg, max) = (5.005, 5.071, 5.120), stdev = 0.060
  CI (99.9%): [3.986, 6.157] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 15.767 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 5.524 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.811 ±(99.9%) 0.007 ms/op
Iteration   1: 4.752 ±(99.9%) 0.016 ms/op
Iteration   2: 4.667 ±(99.9%) 0.011 ms/op
Iteration   3: 4.877 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.765 ±(99.9%) 1.934 ms/op [Average]
  (min, avg, max) = (4.667, 4.765, 4.877), stdev = 0.106
  CI (99.9%): [2.832, 6.699] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 16.126 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 6.407 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.164 ±(99.9%) 0.011 ms/op
Iteration   1: 5.213 ±(99.9%) 0.013 ms/op
Iteration   2: 5.173 ±(99.9%) 0.009 ms/op
Iteration   3: 5.210 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.198 ±(99.9%) 0.406 ms/op [Average]
  (min, avg, max) = (5.173, 5.198, 5.213), stdev = 0.022
  CI (99.9%): [4.792, 5.604] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 18.255 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 6.611 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.714 ±(99.9%) 0.013 ms/op
Iteration   1: 5.820 ±(99.9%) 0.011 ms/op
Iteration   2: 5.830 ±(99.9%) 0.016 ms/op
Iteration   3: 5.855 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.835 ±(99.9%) 0.329 ms/op [Average]
  (min, avg, max) = (5.820, 5.835, 5.855), stdev = 0.018
  CI (99.9%): [5.506, 6.164] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 15.219 ±(99.9%) 0.221 ms/op
# Warmup Iteration   2: 6.194 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.492 ±(99.9%) 0.023 ms/op
Iteration   1: 5.192 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.075 ms/op
                 createUser·p0.50:   4.964 ms/op
                 createUser·p0.90:   6.463 ms/op
                 createUser·p0.95:   7.307 ms/op
                 createUser·p0.99:   9.443 ms/op
                 createUser·p0.999:  25.509 ms/op
                 createUser·p0.9999: 29.049 ms/op
                 createUser·p1.00:   30.736 ms/op

Iteration   2: 5.111 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.954 ms/op
                 createUser·p0.50:   4.882 ms/op
                 createUser·p0.90:   6.300 ms/op
                 createUser·p0.95:   6.996 ms/op
                 createUser·p0.99:   9.208 ms/op
                 createUser·p0.999:  24.098 ms/op
                 createUser·p0.9999: 33.201 ms/op
                 createUser·p1.00:   37.487 ms/op

Iteration   3: 4.955 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.114 ms/op
                 createUser·p0.50:   4.801 ms/op
                 createUser·p0.90:   5.906 ms/op
                 createUser·p0.95:   6.365 ms/op
                 createUser·p0.99:   8.438 ms/op
                 createUser·p0.999:  29.606 ms/op
                 createUser·p0.9999: 32.014 ms/op
                 createUser·p1.00:   32.932 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 188723
  mean =      5.084 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 93 
    [ 2.500,  5.000) = 106344 
    [ 5.000,  7.500) = 76638 
    [ 7.500, 10.000) = 4413 
    [10.000, 12.500) = 741 
    [12.500, 15.000) = 175 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 85 
    [30.000, 32.500) = 70 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.954 ms/op
     p(50.0000) =      4.874 ms/op
     p(90.0000) =      6.210 ms/op
     p(95.0000) =      6.857 ms/op
     p(99.0000) =      9.110 ms/op
     p(99.9000) =     26.509 ms/op
     p(99.9900) =     32.047 ms/op
     p(99.9990) =     34.114 ms/op
     p(99.9999) =     37.487 ms/op
    p(100.0000) =     37.487 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 16.089 ±(99.9%) 0.274 ms/op
# Warmup Iteration   2: 5.713 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.108 ±(99.9%) 0.019 ms/op
Iteration   1: 4.830 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.954 ms/op
                 existUser·p0.50:   4.637 ms/op
                 existUser·p0.90:   5.775 ms/op
                 existUser·p0.95:   6.660 ms/op
                 existUser·p0.99:   9.093 ms/op
                 existUser·p0.999:  18.768 ms/op
                 existUser·p0.9999: 26.632 ms/op
                 existUser·p1.00:   29.032 ms/op

Iteration   2: 4.953 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.065 ms/op
                 existUser·p0.50:   4.743 ms/op
                 existUser·p0.90:   5.972 ms/op
                 existUser·p0.95:   6.717 ms/op
                 existUser·p0.99:   9.994 ms/op
                 existUser·p0.999:  13.365 ms/op
                 existUser·p0.9999: 29.452 ms/op
                 existUser·p1.00:   29.884 ms/op

Iteration   3: 5.107 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.792 ms/op
                 existUser·p0.50:   4.841 ms/op
                 existUser·p0.90:   6.332 ms/op
                 existUser·p0.95:   7.291 ms/op
                 existUser·p0.99:   10.093 ms/op
                 existUser·p0.999:  29.470 ms/op
                 existUser·p0.9999: 33.568 ms/op
                 existUser·p1.00:   36.569 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 193451
  mean =      4.961 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 71 
    [ 2.500,  5.000) = 125347 
    [ 5.000,  7.500) = 61273 
    [ 7.500, 10.000) = 5024 
    [10.000, 12.500) = 1296 
    [12.500, 15.000) = 176 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 40 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      4.735 ms/op
     p(90.0000) =      6.038 ms/op
     p(95.0000) =      6.889 ms/op
     p(99.0000) =      9.716 ms/op
     p(99.9000) =     20.737 ms/op
     p(99.9900) =     32.440 ms/op
     p(99.9990) =     35.712 ms/op
     p(99.9999) =     36.569 ms/op
    p(100.0000) =     36.569 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 15.767 ±(99.9%) 0.254 ms/op
# Warmup Iteration   2: 5.660 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.194 ±(99.9%) 0.017 ms/op
Iteration   1: 5.141 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.359 ms/op
                 getUser·p0.50:   4.801 ms/op
                 getUser·p0.90:   6.472 ms/op
                 getUser·p0.95:   7.537 ms/op
                 getUser·p0.99:   12.468 ms/op
                 getUser·p0.999:  24.314 ms/op
                 getUser·p0.9999: 27.354 ms/op
                 getUser·p1.00:   28.344 ms/op

Iteration   2: 4.869 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.257 ms/op
                 getUser·p0.50:   4.702 ms/op
                 getUser·p0.90:   5.800 ms/op
                 getUser·p0.95:   6.316 ms/op
                 getUser·p0.99:   8.602 ms/op
                 getUser·p0.999:  16.685 ms/op
                 getUser·p0.9999: 28.431 ms/op
                 getUser·p1.00:   29.524 ms/op

Iteration   3: 4.990 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.322 ms/op
                 getUser·p0.50:   4.792 ms/op
                 getUser·p0.90:   5.947 ms/op
                 getUser·p0.95:   6.685 ms/op
                 getUser·p0.99:   8.929 ms/op
                 getUser·p0.999:  22.418 ms/op
                 getUser·p0.9999: 27.176 ms/op
                 getUser·p1.00:   28.017 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 191858
  mean =      4.998 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 120995 
    [ 5.000,  7.500) = 64319 
    [ 7.500, 10.000) = 4723 
    [10.000, 12.500) = 984 
    [12.500, 15.000) = 446 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 123 

  Percentiles, ms/op:
      p(0.0000) =      2.257 ms/op
     p(50.0000) =      4.760 ms/op
     p(90.0000) =      6.054 ms/op
     p(95.0000) =      6.857 ms/op
     p(99.0000) =      9.847 ms/op
     p(99.9000) =     23.162 ms/op
     p(99.9900) =     27.656 ms/op
     p(99.9990) =     29.494 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 17.471 ±(99.9%) 0.278 ms/op
# Warmup Iteration   2: 6.909 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 6.184 ±(99.9%) 0.023 ms/op
Iteration   1: 6.010 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.228 ms/op
                 listUser·p0.50:   5.792 ms/op
                 listUser·p0.90:   7.012 ms/op
                 listUser·p0.95:   7.692 ms/op
                 listUser·p0.99:   11.256 ms/op
                 listUser·p0.999:  24.238 ms/op
                 listUser·p0.9999: 31.250 ms/op
                 listUser·p1.00:   31.883 ms/op

Iteration   2: 6.016 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.703 ms/op
                 listUser·p0.50:   5.792 ms/op
                 listUser·p0.90:   7.176 ms/op
                 listUser·p0.95:   8.077 ms/op
                 listUser·p0.99:   10.813 ms/op
                 listUser·p0.999:  25.678 ms/op
                 listUser·p0.9999: 28.717 ms/op
                 listUser·p1.00:   29.688 ms/op

Iteration   3: 5.925 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.953 ms/op
                 listUser·p0.50:   5.702 ms/op
                 listUser·p0.90:   6.939 ms/op
                 listUser·p0.95:   7.799 ms/op
                 listUser·p0.99:   11.239 ms/op
                 listUser·p0.999:  23.884 ms/op
                 listUser·p0.9999: 27.348 ms/op
                 listUser·p1.00:   29.065 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 160559
  mean =      5.983 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 22092 
    [ 5.000,  7.500) = 128185 
    [ 7.500, 10.000) = 7598 
    [10.000, 12.500) = 1826 
    [12.500, 15.000) = 445 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 118 
    [25.000, 27.500) = 87 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.228 ms/op
     p(50.0000) =      5.759 ms/op
     p(90.0000) =      7.037 ms/op
     p(95.0000) =      7.856 ms/op
     p(99.0000) =     11.092 ms/op
     p(99.9000) =     24.656 ms/op
     p(99.9900) =     29.680 ms/op
     p(99.9990) =     31.725 ms/op
     p(99.9999) =     31.883 ms/op
    p(100.0000) =     31.883 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.014 ± 2.124  ops/ms
ClientPb.existUser                       thrpt       3   6.517 ± 1.518  ops/ms
ClientPb.getUser                         thrpt       3   6.311 ± 2.488  ops/ms
ClientPb.listUser                        thrpt       3   5.340 ± 1.795  ops/ms
ClientPb.createUser                       avgt       3   5.071 ± 1.086   ms/op
ClientPb.existUser                        avgt       3   4.765 ± 1.934   ms/op
ClientPb.getUser                          avgt       3   5.198 ± 0.406   ms/op
ClientPb.listUser                         avgt       3   5.835 ± 0.329   ms/op
ClientPb.createUser                     sample  188723   5.084 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.954           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.874           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.210           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.857           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.110           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.509           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.047           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.487           ms/op
ClientPb.existUser                      sample  193451   4.961 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.065           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.735           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.038           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.889           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.716           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.737           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.440           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.569           ms/op
ClientPb.getUser                        sample  191858   4.998 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.257           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.760           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.054           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.857           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.847           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.162           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.656           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.524           ms/op
ClientPb.listUser                       sample  160559   5.983 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.228           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.759           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.037           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.856           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.092           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.656           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.680           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.883           ms/op
