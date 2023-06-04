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
# Warmup Iteration   1: 2.486 ops/ms
# Warmup Iteration   2: 5.660 ops/ms
# Warmup Iteration   3: 8.890 ops/ms
Iteration   1: 9.327 ops/ms
Iteration   2: 9.726 ops/ms
Iteration   3: 10.229 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.761 ±(99.9%) 8.248 ops/ms [Average]
  (min, avg, max) = (9.327, 9.761, 10.229), stdev = 0.452
  CI (99.9%): [1.512, 18.009] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.411 ops/ms
# Warmup Iteration   2: 9.128 ops/ms
# Warmup Iteration   3: 9.875 ops/ms
Iteration   1: 9.862 ops/ms
Iteration   2: 10.458 ops/ms
Iteration   3: 10.322 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.214 ±(99.9%) 5.700 ops/ms [Average]
  (min, avg, max) = (9.862, 10.214, 10.458), stdev = 0.312
  CI (99.9%): [4.514, 15.914] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.365 ops/ms
# Warmup Iteration   2: 8.678 ops/ms
# Warmup Iteration   3: 9.461 ops/ms
Iteration   1: 9.967 ops/ms
Iteration   2: 9.810 ops/ms
Iteration   3: 10.089 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.955 ±(99.9%) 2.546 ops/ms [Average]
  (min, avg, max) = (9.810, 9.955, 10.089), stdev = 0.140
  CI (99.9%): [7.409, 12.502] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.412 ops/ms
# Warmup Iteration   2: 7.326 ops/ms
# Warmup Iteration   3: 8.427 ops/ms
Iteration   1: 8.671 ops/ms
Iteration   2: 8.430 ops/ms
Iteration   3: 8.542 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.548 ±(99.9%) 2.203 ops/ms [Average]
  (min, avg, max) = (8.430, 8.548, 8.671), stdev = 0.121
  CI (99.9%): [6.345, 10.750] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.424 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.482 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.276 ±(99.9%) 0.002 ms/op
Iteration   1: 3.274 ±(99.9%) 0.008 ms/op
Iteration   2: 3.264 ±(99.9%) 0.006 ms/op
Iteration   3: 3.166 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.235 ±(99.9%) 1.088 ms/op [Average]
  (min, avg, max) = (3.166, 3.235, 3.274), stdev = 0.060
  CI (99.9%): [2.147, 4.322] (assumes normal distribution)


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
# Warmup Iteration   1: 7.180 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.389 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.043 ±(99.9%) 0.001 ms/op
Iteration   1: 3.088 ±(99.9%) 0.007 ms/op
Iteration   2: 2.996 ±(99.9%) 0.005 ms/op
Iteration   3: 3.107 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.063 ±(99.9%) 1.078 ms/op [Average]
  (min, avg, max) = (2.996, 3.063, 3.107), stdev = 0.059
  CI (99.9%): [1.985, 4.142] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.929 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.511 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.341 ±(99.9%) 0.005 ms/op
Iteration   1: 3.210 ±(99.9%) 0.002 ms/op
Iteration   2: 3.173 ±(99.9%) 0.008 ms/op
Iteration   3: 3.321 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.235 ±(99.9%) 1.403 ms/op [Average]
  (min, avg, max) = (3.173, 3.235, 3.321), stdev = 0.077
  CI (99.9%): [1.832, 4.638] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.551 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.189 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.938 ±(99.9%) 0.006 ms/op
Iteration   1: 3.725 ±(99.9%) 0.009 ms/op
Iteration   2: 3.758 ±(99.9%) 0.011 ms/op
Iteration   3: 3.847 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.777 ±(99.9%) 1.153 ms/op [Average]
  (min, avg, max) = (3.725, 3.777, 3.847), stdev = 0.063
  CI (99.9%): [2.623, 4.930] (assumes normal distribution)


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
# Warmup Iteration   1: 7.990 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 4.409 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.284 ±(99.9%) 0.010 ms/op
Iteration   1: 3.178 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.432 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.404 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  12.993 ms/op
                 createUser·p0.9999: 23.233 ms/op
                 createUser·p1.00:   25.330 ms/op

Iteration   2: 3.320 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.651 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.875 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.644 ms/op
                 createUser·p0.999:  18.580 ms/op
                 createUser·p0.9999: 22.462 ms/op
                 createUser·p1.00:   25.756 ms/op

Iteration   3: 3.412 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.010 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   3.944 ms/op
                 createUser·p0.95:   4.751 ms/op
                 createUser·p0.99:   5.833 ms/op
                 createUser·p0.999:  15.860 ms/op
                 createUser·p0.9999: 22.172 ms/op
                 createUser·p1.00:   26.870 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 290574
  mean =      3.301 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23273 
    [ 2.500,  5.000) = 259111 
    [ 5.000,  7.500) = 7253 
    [ 7.500, 10.000) = 433 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 220 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.010 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =     15.834 ms/op
     p(99.9900) =     22.610 ms/op
     p(99.9990) =     25.370 ms/op
     p(99.9999) =     26.870 ms/op
    p(100.0000) =     26.870 ms/op


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
# Warmup Iteration   1: 7.357 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.346 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.007 ms/op
Iteration   1: 3.077 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.468 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   4.833 ms/op
                 existUser·p0.999:  9.961 ms/op
                 existUser·p0.9999: 24.780 ms/op
                 existUser·p1.00:   25.723 ms/op

Iteration   2: 3.203 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.565 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   4.043 ms/op
                 existUser·p0.99:   5.587 ms/op
                 existUser·p0.999:  10.273 ms/op
                 existUser·p0.9999: 23.265 ms/op
                 existUser·p1.00:   24.543 ms/op

Iteration   3: 3.181 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.368 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   4.055 ms/op
                 existUser·p0.99:   6.095 ms/op
                 existUser·p0.999:  13.418 ms/op
                 existUser·p0.9999: 19.262 ms/op
                 existUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304440
  mean =      3.153 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22118 
    [ 2.500,  5.000) = 276784 
    [ 5.000,  7.500) = 4678 
    [ 7.500, 10.000) = 461 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.368 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     13.020 ms/op
     p(99.9900) =     23.797 ms/op
     p(99.9990) =     25.002 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


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
# Warmup Iteration   1: 8.526 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.512 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.282 ±(99.9%) 0.010 ms/op
Iteration   1: 3.294 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.352 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   4.055 ms/op
                 getUser·p0.99:   6.840 ms/op
                 getUser·p0.999:  17.038 ms/op
                 getUser·p0.9999: 19.998 ms/op
                 getUser·p1.00:   20.939 ms/op

Iteration   2: 3.279 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.417 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   5.865 ms/op
                 getUser·p0.999:  18.645 ms/op
                 getUser·p0.9999: 27.992 ms/op
                 getUser·p1.00:   29.524 ms/op

Iteration   3: 3.246 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.620 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   4.076 ms/op
                 getUser·p0.99:   5.595 ms/op
                 getUser·p0.999:  13.333 ms/op
                 getUser·p0.9999: 20.883 ms/op
                 getUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 292982
  mean =      3.273 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7042 
    [ 2.500,  5.000) = 278709 
    [ 5.000,  7.500) = 5947 
    [ 7.500, 10.000) = 775 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 114 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.352 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      6.268 ms/op
     p(99.9000) =     15.958 ms/op
     p(99.9900) =     26.041 ms/op
     p(99.9990) =     28.470 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


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
# Warmup Iteration   1: 9.602 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 4.291 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.837 ±(99.9%) 0.011 ms/op
Iteration   1: 3.766 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.184 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.018 ms/op
                 listUser·p0.95:   4.359 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  17.859 ms/op
                 listUser·p0.9999: 20.546 ms/op
                 listUser·p1.00:   20.906 ms/op

Iteration   2: 3.754 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.339 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  14.757 ms/op
                 listUser·p0.9999: 17.203 ms/op
                 listUser·p1.00:   17.400 ms/op

Iteration   3: 3.748 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.104 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  13.484 ms/op
                 listUser·p0.9999: 20.299 ms/op
                 listUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255378
  mean =      3.756 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45 
    [ 2.500,  5.000) = 248346 
    [ 5.000,  7.500) = 5072 
    [ 7.500, 10.000) = 1281 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 223 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.184 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.047 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     14.844 ms/op
     p(99.9900) =     20.283 ms/op
     p(99.9990) =     20.808 ms/op
     p(99.9999) =     20.906 ms/op
    p(100.0000) =     20.906 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.761 ± 8.248  ops/ms
ClientPb.existUser                       thrpt       3  10.214 ± 5.700  ops/ms
ClientPb.getUser                         thrpt       3   9.955 ± 2.546  ops/ms
ClientPb.listUser                        thrpt       3   8.548 ± 2.203  ops/ms
ClientPb.createUser                       avgt       3   3.235 ± 1.088   ms/op
ClientPb.existUser                        avgt       3   3.063 ± 1.078   ms/op
ClientPb.getUser                          avgt       3   3.235 ± 1.403   ms/op
ClientPb.listUser                         avgt       3   3.777 ± 1.153   ms/op
ClientPb.createUser                     sample  290574   3.301 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.010           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.224           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.744           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.235           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.718           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.834           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.610           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.870           ms/op
ClientPb.existUser                      sample  304440   3.153 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.368           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.486           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.949           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.595           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.020           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.797           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.723           ms/op
ClientPb.getUser                        sample  292982   3.273 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.352           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.158           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.588           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.977           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.268           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.958           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.041           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.524           ms/op
ClientPb.listUser                       sample  255378   3.756 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.184           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.658           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.047           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.021           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.844           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.283           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.906           ms/op
