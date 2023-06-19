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
# Warmup Iteration   1: 2.547 ops/ms
# Warmup Iteration   2: 5.404 ops/ms
# Warmup Iteration   3: 8.910 ops/ms
Iteration   1: 10.045 ops/ms
Iteration   2: 9.756 ops/ms
Iteration   3: 9.955 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.919 ±(99.9%) 2.702 ops/ms [Average]
  (min, avg, max) = (9.756, 9.919, 10.045), stdev = 0.148
  CI (99.9%): [7.217, 12.620] (assumes normal distribution)


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
# Warmup Iteration   1: 3.605 ops/ms
# Warmup Iteration   2: 8.934 ops/ms
# Warmup Iteration   3: 10.216 ops/ms
Iteration   1: 10.325 ops/ms
Iteration   2: 10.020 ops/ms
Iteration   3: 10.502 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.282 ±(99.9%) 4.448 ops/ms [Average]
  (min, avg, max) = (10.020, 10.282, 10.502), stdev = 0.244
  CI (99.9%): [5.835, 14.730] (assumes normal distribution)


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
# Warmup Iteration   1: 3.201 ops/ms
# Warmup Iteration   2: 9.211 ops/ms
# Warmup Iteration   3: 9.529 ops/ms
Iteration   1: 9.985 ops/ms
Iteration   2: 10.004 ops/ms
Iteration   3: 10.120 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.036 ±(99.9%) 1.332 ops/ms [Average]
  (min, avg, max) = (9.985, 10.036, 10.120), stdev = 0.073
  CI (99.9%): [8.704, 11.368] (assumes normal distribution)


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
# Warmup Iteration   1: 2.904 ops/ms
# Warmup Iteration   2: 7.437 ops/ms
# Warmup Iteration   3: 8.149 ops/ms
Iteration   1: 8.451 ops/ms
Iteration   2: 8.553 ops/ms
Iteration   3: 8.570 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.525 ±(99.9%) 1.177 ops/ms [Average]
  (min, avg, max) = (8.451, 8.525, 8.570), stdev = 0.065
  CI (99.9%): [7.348, 9.701] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.869 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.574 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.308 ±(99.9%) 0.011 ms/op
Iteration   1: 3.323 ±(99.9%) 0.007 ms/op
Iteration   2: 3.237 ±(99.9%) 0.003 ms/op
Iteration   3: 3.339 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.299 ±(99.9%) 1.002 ms/op [Average]
  (min, avg, max) = (3.237, 3.299, 3.339), stdev = 0.055
  CI (99.9%): [2.297, 4.302] (assumes normal distribution)


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
# Warmup Iteration   1: 7.491 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.401 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.170 ±(99.9%) 0.003 ms/op
Iteration   1: 3.156 ±(99.9%) 0.003 ms/op
Iteration   2: 3.190 ±(99.9%) 0.003 ms/op
Iteration   3: 3.026 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.124 ±(99.9%) 1.582 ms/op [Average]
  (min, avg, max) = (3.026, 3.124, 3.190), stdev = 0.087
  CI (99.9%): [1.542, 4.706] (assumes normal distribution)


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
# Warmup Iteration   1: 8.291 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.497 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.435 ±(99.9%) 0.003 ms/op
Iteration   1: 3.159 ±(99.9%) 0.003 ms/op
Iteration   2: 3.270 ±(99.9%) 0.006 ms/op
Iteration   3: 3.274 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.234 ±(99.9%) 1.194 ms/op [Average]
  (min, avg, max) = (3.159, 3.234, 3.274), stdev = 0.065
  CI (99.9%): [2.041, 4.428] (assumes normal distribution)


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
# Warmup Iteration   1: 9.657 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.061 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.888 ±(99.9%) 0.003 ms/op
Iteration   1: 3.886 ±(99.9%) 0.006 ms/op
Iteration   2: 3.817 ±(99.9%) 0.007 ms/op
Iteration   3: 3.772 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.825 ±(99.9%) 1.044 ms/op [Average]
  (min, avg, max) = (3.772, 3.825, 3.886), stdev = 0.057
  CI (99.9%): [2.780, 4.869] (assumes normal distribution)


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
# Warmup Iteration   1: 8.723 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 4.218 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.334 ±(99.9%) 0.010 ms/op
Iteration   1: 3.401 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.122 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   5.702 ms/op
                 createUser·p0.999:  18.610 ms/op
                 createUser·p0.9999: 23.553 ms/op
                 createUser·p1.00:   24.150 ms/op

Iteration   2: 3.128 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.677 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.420 ms/op
                 createUser·p0.95:   3.641 ms/op
                 createUser·p0.99:   5.218 ms/op
                 createUser·p0.999:  14.846 ms/op
                 createUser·p0.9999: 28.093 ms/op
                 createUser·p1.00:   28.705 ms/op

Iteration   3: 3.187 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.292 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.314 ms/op
                 createUser·p0.95:   3.539 ms/op
                 createUser·p0.99:   5.100 ms/op
                 createUser·p0.999:  18.186 ms/op
                 createUser·p0.9999: 22.872 ms/op
                 createUser·p1.00:   23.233 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296768
  mean =      3.234 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18865 
    [ 2.500,  5.000) = 273229 
    [ 5.000,  7.500) = 3876 
    [ 7.500, 10.000) = 344 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 136 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.122 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =     17.932 ms/op
     p(99.9900) =     27.034 ms/op
     p(99.9990) =     28.640 ms/op
     p(99.9999) =     28.705 ms/op
    p(100.0000) =     28.705 ms/op


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
# Warmup Iteration   1: 7.240 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.521 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.007 ms/op
Iteration   1: 3.119 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.350 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   6.185 ms/op
                 existUser·p0.999:  9.880 ms/op
                 existUser·p0.9999: 20.176 ms/op
                 existUser·p1.00:   21.332 ms/op

Iteration   2: 3.125 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.025 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   5.202 ms/op
                 existUser·p0.999:  8.140 ms/op
                 existUser·p0.9999: 22.310 ms/op
                 existUser·p1.00:   23.200 ms/op

Iteration   3: 3.204 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.194 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   5.898 ms/op
                 existUser·p0.999:  13.582 ms/op
                 existUser·p0.9999: 24.971 ms/op
                 existUser·p1.00:   25.887 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304724
  mean =      3.149 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11027 
    [ 2.500,  5.000) = 288049 
    [ 5.000,  7.500) = 4840 
    [ 7.500, 10.000) = 386 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 146 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.025 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.408 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     13.451 ms/op
     p(99.9900) =     24.216 ms/op
     p(99.9990) =     25.361 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


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
# Warmup Iteration   1: 7.785 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.580 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.233 ±(99.9%) 0.009 ms/op
Iteration   1: 3.340 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.438 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.830 ms/op
                 getUser·p0.95:   5.251 ms/op
                 getUser·p0.99:   6.496 ms/op
                 getUser·p0.999:  17.143 ms/op
                 getUser·p0.9999: 21.373 ms/op
                 getUser·p1.00:   23.036 ms/op

Iteration   2: 3.341 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.135 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.867 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   6.177 ms/op
                 getUser·p0.999:  19.305 ms/op
                 getUser·p0.9999: 22.938 ms/op
                 getUser·p1.00:   23.921 ms/op

Iteration   3: 3.199 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.174 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   5.767 ms/op
                 getUser·p0.999:  15.655 ms/op
                 getUser·p0.9999: 24.380 ms/op
                 getUser·p1.00:   26.018 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 291530
  mean =      3.292 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18982 
    [ 2.500,  5.000) = 262008 
    [ 5.000,  7.500) = 9520 
    [ 7.500, 10.000) = 550 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 132 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.135 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      6.316 ms/op
     p(99.9000) =     15.677 ms/op
     p(99.9900) =     23.293 ms/op
     p(99.9990) =     25.827 ms/op
     p(99.9999) =     26.018 ms/op
    p(100.0000) =     26.018 ms/op


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
# Warmup Iteration   1: 8.879 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.180 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.946 ±(99.9%) 0.012 ms/op
Iteration   1: 3.833 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.419 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.166 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  16.089 ms/op
                 listUser·p0.9999: 22.609 ms/op
                 listUser·p1.00:   23.396 ms/op

Iteration   2: 3.831 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.081 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   7.340 ms/op
                 listUser·p0.999:  14.917 ms/op
                 listUser·p0.9999: 21.557 ms/op
                 listUser·p1.00:   23.069 ms/op

Iteration   3: 3.793 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.294 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   6.578 ms/op
                 listUser·p0.999:  13.418 ms/op
                 listUser·p0.9999: 15.024 ms/op
                 listUser·p1.00:   15.204 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251239
  mean =      3.819 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 90 
    [ 2.500,  5.000) = 242715 
    [ 5.000,  7.500) = 6454 
    [ 7.500, 10.000) = 1289 
    [10.000, 12.500) = 175 
    [12.500, 15.000) = 336 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.419 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.166 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     14.402 ms/op
     p(99.9900) =     21.258 ms/op
     p(99.9990) =     23.133 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.919 ± 2.702  ops/ms
ClientPb.existUser                       thrpt       3  10.282 ± 4.448  ops/ms
ClientPb.getUser                         thrpt       3  10.036 ± 1.332  ops/ms
ClientPb.listUser                        thrpt       3   8.525 ± 1.177  ops/ms
ClientPb.createUser                       avgt       3   3.299 ± 1.002   ms/op
ClientPb.existUser                        avgt       3   3.124 ± 1.582   ms/op
ClientPb.getUser                          avgt       3   3.234 ± 1.194   ms/op
ClientPb.listUser                         avgt       3   3.825 ± 1.044   ms/op
ClientPb.createUser                     sample  296768   3.234 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.122           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.637           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.912           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.448           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.932           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.034           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.705           ms/op
ClientPb.existUser                      sample  304724   3.149 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.025           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.408           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.686           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.726           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.451           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.216           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.887           ms/op
ClientPb.getUser                        sample  291530   3.292 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.135           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.731           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.334           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.316           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.677           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.293           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.018           ms/op
ClientPb.listUser                       sample  251239   3.819 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.419           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.727           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.166           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.102           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.402           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.258           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.396           ms/op
