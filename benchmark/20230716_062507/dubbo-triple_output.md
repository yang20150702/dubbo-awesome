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
# Warmup Iteration   1: 2.548 ops/ms
# Warmup Iteration   2: 6.127 ops/ms
# Warmup Iteration   3: 8.921 ops/ms
Iteration   1: 10.042 ops/ms
Iteration   2: 9.600 ops/ms
Iteration   3: 10.235 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.959 ±(99.9%) 5.942 ops/ms [Average]
  (min, avg, max) = (9.600, 9.959, 10.235), stdev = 0.326
  CI (99.9%): [4.017, 15.902] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.308 ops/ms
# Warmup Iteration   2: 9.095 ops/ms
# Warmup Iteration   3: 9.707 ops/ms
Iteration   1: 10.249 ops/ms
Iteration   2: 10.482 ops/ms
Iteration   3: 10.337 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.356 ±(99.9%) 2.143 ops/ms [Average]
  (min, avg, max) = (10.249, 10.356, 10.482), stdev = 0.117
  CI (99.9%): [8.213, 12.499] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.494 ops/ms
# Warmup Iteration   2: 9.028 ops/ms
# Warmup Iteration   3: 9.307 ops/ms
Iteration   1: 9.721 ops/ms
Iteration   2: 10.103 ops/ms
Iteration   3: 10.112 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.979 ±(99.9%) 4.080 ops/ms [Average]
  (min, avg, max) = (9.721, 9.979, 10.112), stdev = 0.224
  CI (99.9%): [5.898, 14.059] (assumes normal distribution)


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
# Warmup Iteration   1: 3.171 ops/ms
# Warmup Iteration   2: 7.441 ops/ms
# Warmup Iteration   3: 8.452 ops/ms
Iteration   1: 8.494 ops/ms
Iteration   2: 8.512 ops/ms
Iteration   3: 8.388 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.464 ±(99.9%) 1.217 ops/ms [Average]
  (min, avg, max) = (8.388, 8.464, 8.512), stdev = 0.067
  CI (99.9%): [7.248, 9.681] (assumes normal distribution)


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
# Warmup Iteration   1: 8.504 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.536 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.426 ±(99.9%) 0.004 ms/op
Iteration   1: 3.196 ±(99.9%) 0.003 ms/op
Iteration   2: 3.296 ±(99.9%) 0.007 ms/op
Iteration   3: 3.360 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.284 ±(99.9%) 1.506 ms/op [Average]
  (min, avg, max) = (3.196, 3.284, 3.360), stdev = 0.083
  CI (99.9%): [1.778, 4.790] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.335 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.450 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.187 ±(99.9%) 0.005 ms/op
Iteration   1: 3.215 ±(99.9%) 0.006 ms/op
Iteration   2: 3.131 ±(99.9%) 0.005 ms/op
Iteration   3: 3.075 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.140 ±(99.9%) 1.282 ms/op [Average]
  (min, avg, max) = (3.075, 3.140, 3.215), stdev = 0.070
  CI (99.9%): [1.858, 4.422] (assumes normal distribution)


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
# Warmup Iteration   1: 8.564 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.636 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.550 ±(99.9%) 0.006 ms/op
Iteration   1: 3.255 ±(99.9%) 0.005 ms/op
Iteration   2: 3.252 ±(99.9%) 0.006 ms/op
Iteration   3: 3.364 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.290 ±(99.9%) 1.163 ms/op [Average]
  (min, avg, max) = (3.252, 3.290, 3.364), stdev = 0.064
  CI (99.9%): [2.127, 4.453] (assumes normal distribution)


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
# Warmup Iteration   1: 10.209 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.372 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.766 ±(99.9%) 0.006 ms/op
Iteration   1: 3.736 ±(99.9%) 0.009 ms/op
Iteration   2: 3.771 ±(99.9%) 0.007 ms/op
Iteration   3: 3.758 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.755 ±(99.9%) 0.321 ms/op [Average]
  (min, avg, max) = (3.736, 3.755, 3.771), stdev = 0.018
  CI (99.9%): [3.434, 4.076] (assumes normal distribution)


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
# Warmup Iteration   1: 8.271 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.906 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.341 ±(99.9%) 0.009 ms/op
Iteration   1: 3.193 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.984 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   5.898 ms/op
                 createUser·p0.999:  12.157 ms/op
                 createUser·p0.9999: 20.840 ms/op
                 createUser·p1.00:   21.332 ms/op

Iteration   2: 3.378 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.303 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.875 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   6.013 ms/op
                 createUser·p0.999:  20.578 ms/op
                 createUser·p0.9999: 25.955 ms/op
                 createUser·p1.00:   26.378 ms/op

Iteration   3: 3.248 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.647 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  22.123 ms/op
                 createUser·p0.9999: 24.554 ms/op
                 createUser·p1.00:   25.330 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 293125
  mean =      3.271 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18885 
    [ 2.500,  5.000) = 267424 
    [ 5.000,  7.500) = 5794 
    [ 7.500, 10.000) = 581 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 132 
    [22.500, 25.000) = 116 
    [25.000, 27.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      0.984 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      4.182 ms/op
     p(99.0000) =      5.724 ms/op
     p(99.9000) =     19.980 ms/op
     p(99.9900) =     25.549 ms/op
     p(99.9990) =     26.221 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


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
# Warmup Iteration   1: 6.671 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.514 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.210 ±(99.9%) 0.008 ms/op
Iteration   1: 3.161 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.198 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   5.472 ms/op
                 existUser·p0.999:  9.683 ms/op
                 existUser·p0.9999: 24.958 ms/op
                 existUser·p1.00:   25.854 ms/op

Iteration   2: 3.135 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.986 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   5.677 ms/op
                 existUser·p0.999:  9.716 ms/op
                 existUser·p0.9999: 21.096 ms/op
                 existUser·p1.00:   21.889 ms/op

Iteration   3: 3.076 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.353 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.473 ms/op
                 existUser·p0.99:   4.465 ms/op
                 existUser·p0.999:  12.408 ms/op
                 existUser·p0.9999: 21.065 ms/op
                 existUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307003
  mean =      3.123 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14514 
    [ 2.500,  5.000) = 288013 
    [ 5.000,  7.500) = 3544 
    [ 7.500, 10.000) = 513 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.353 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.379 ms/op
     p(95.0000) =      3.621 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =     12.370 ms/op
     p(99.9900) =     22.826 ms/op
     p(99.9990) =     25.590 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


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
# Warmup Iteration   1: 8.390 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.498 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.274 ±(99.9%) 0.009 ms/op
Iteration   1: 3.384 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.219 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.940 ms/op
                 getUser·p0.95:   4.702 ms/op
                 getUser·p0.99:   6.914 ms/op
                 getUser·p0.999:  17.848 ms/op
                 getUser·p0.9999: 28.246 ms/op
                 getUser·p1.00:   28.770 ms/op

Iteration   2: 3.202 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.800 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   5.652 ms/op
                 getUser·p0.999:  9.651 ms/op
                 getUser·p0.9999: 25.199 ms/op
                 getUser·p1.00:   27.525 ms/op

Iteration   3: 3.189 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.204 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   5.890 ms/op
                 getUser·p0.999:  15.516 ms/op
                 getUser·p0.9999: 21.791 ms/op
                 getUser·p1.00:   25.854 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294855
  mean =      3.256 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7458 
    [ 2.500,  5.000) = 279698 
    [ 5.000,  7.500) = 6910 
    [ 7.500, 10.000) = 398 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      4.100 ms/op
     p(99.0000) =      6.250 ms/op
     p(99.9000) =     15.483 ms/op
     p(99.9900) =     27.414 ms/op
     p(99.9990) =     28.644 ms/op
     p(99.9999) =     28.770 ms/op
    p(100.0000) =     28.770 ms/op


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
# Warmup Iteration   1: 9.065 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.187 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.862 ±(99.9%) 0.012 ms/op
Iteration   1: 3.899 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.174 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   7.332 ms/op
                 listUser·p0.999:  15.122 ms/op
                 listUser·p0.9999: 22.512 ms/op
                 listUser·p1.00:   23.036 ms/op

Iteration   2: 3.790 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.224 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.145 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  14.476 ms/op
                 listUser·p0.9999: 18.907 ms/op
                 listUser·p1.00:   20.185 ms/op

Iteration   3: 3.746 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.306 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   4.030 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  14.025 ms/op
                 listUser·p0.9999: 21.544 ms/op
                 listUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251829
  mean =      3.811 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 59 
    [ 2.500,  5.000) = 243861 
    [ 5.000,  7.500) = 5955 
    [ 7.500, 10.000) = 1209 
    [10.000, 12.500) = 234 
    [12.500, 15.000) = 320 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.174 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.178 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     14.440 ms/op
     p(99.9900) =     21.561 ms/op
     p(99.9990) =     22.691 ms/op
     p(99.9999) =     23.036 ms/op
    p(100.0000) =     23.036 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.959 ± 5.942  ops/ms
ClientPb.existUser                       thrpt       3  10.356 ± 2.143  ops/ms
ClientPb.getUser                         thrpt       3   9.979 ± 4.080  ops/ms
ClientPb.listUser                        thrpt       3   8.464 ± 1.217  ops/ms
ClientPb.createUser                       avgt       3   3.284 ± 1.506   ms/op
ClientPb.existUser                        avgt       3   3.140 ± 1.282   ms/op
ClientPb.getUser                          avgt       3   3.290 ± 1.163   ms/op
ClientPb.listUser                         avgt       3   3.755 ± 0.321   ms/op
ClientPb.createUser                     sample  293125   3.271 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.984           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.727           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.182           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.724           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.980           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.549           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.378           ms/op
ClientPb.existUser                      sample  307003   3.123 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.353           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.379           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.621           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.448           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.370           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.826           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.854           ms/op
ClientPb.getUser                        sample  294855   3.256 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.800           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.588           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.100           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.250           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.483           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.414           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.770           ms/op
ClientPb.listUser                       sample  251829   3.811 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.174           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.678           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.178           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.037           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.440           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.561           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.036           ms/op
