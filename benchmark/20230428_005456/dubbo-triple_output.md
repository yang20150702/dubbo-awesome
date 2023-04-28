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
# Warmup Iteration   1: 2.118 ops/ms
# Warmup Iteration   2: 6.013 ops/ms
# Warmup Iteration   3: 8.963 ops/ms
Iteration   1: 9.860 ops/ms
Iteration   2: 9.771 ops/ms
Iteration   3: 9.802 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.811 ±(99.9%) 0.820 ops/ms [Average]
  (min, avg, max) = (9.771, 9.811, 9.860), stdev = 0.045
  CI (99.9%): [8.991, 10.631] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.524 ops/ms
# Warmup Iteration   2: 8.945 ops/ms
# Warmup Iteration   3: 9.893 ops/ms
Iteration   1: 10.250 ops/ms
Iteration   2: 9.842 ops/ms
Iteration   3: 9.962 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.018 ±(99.9%) 3.831 ops/ms [Average]
  (min, avg, max) = (9.842, 10.018, 10.250), stdev = 0.210
  CI (99.9%): [6.187, 13.849] (assumes normal distribution)


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
# Warmup Iteration   1: 3.370 ops/ms
# Warmup Iteration   2: 8.860 ops/ms
# Warmup Iteration   3: 9.707 ops/ms
Iteration   1: 9.797 ops/ms
Iteration   2: 9.974 ops/ms
Iteration   3: 10.098 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.956 ±(99.9%) 2.754 ops/ms [Average]
  (min, avg, max) = (9.797, 9.956, 10.098), stdev = 0.151
  CI (99.9%): [7.202, 12.711] (assumes normal distribution)


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
# Warmup Iteration   1: 3.113 ops/ms
# Warmup Iteration   2: 6.679 ops/ms
# Warmup Iteration   3: 8.281 ops/ms
Iteration   1: 8.525 ops/ms
Iteration   2: 8.404 ops/ms
Iteration   3: 8.518 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.482 ±(99.9%) 1.239 ops/ms [Average]
  (min, avg, max) = (8.404, 8.482, 8.525), stdev = 0.068
  CI (99.9%): [7.243, 9.722] (assumes normal distribution)


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
# Warmup Iteration   1: 8.855 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 3.628 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.454 ±(99.9%) 0.004 ms/op
Iteration   1: 3.189 ±(99.9%) 0.009 ms/op
Iteration   2: 3.231 ±(99.9%) 0.007 ms/op
Iteration   3: 3.294 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.238 ±(99.9%) 0.965 ms/op [Average]
  (min, avg, max) = (3.189, 3.238, 3.294), stdev = 0.053
  CI (99.9%): [2.273, 4.203] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.907 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.500 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.137 ±(99.9%) 0.007 ms/op
Iteration   1: 3.203 ±(99.9%) 0.006 ms/op
Iteration   2: 3.033 ±(99.9%) 0.008 ms/op
Iteration   3: 3.094 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.110 ±(99.9%) 1.568 ms/op [Average]
  (min, avg, max) = (3.033, 3.110, 3.203), stdev = 0.086
  CI (99.9%): [1.543, 4.678] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 9.040 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.689 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.360 ±(99.9%) 0.002 ms/op
Iteration   1: 3.277 ±(99.9%) 0.004 ms/op
Iteration   2: 3.254 ±(99.9%) 0.006 ms/op
Iteration   3: 3.213 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.248 ±(99.9%) 0.593 ms/op [Average]
  (min, avg, max) = (3.213, 3.248, 3.277), stdev = 0.032
  CI (99.9%): [2.655, 3.841] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.964 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.393 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.900 ±(99.9%) 0.006 ms/op
Iteration   1: 3.789 ±(99.9%) 0.009 ms/op
Iteration   2: 3.721 ±(99.9%) 0.011 ms/op
Iteration   3: 3.809 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.773 ±(99.9%) 0.846 ms/op [Average]
  (min, avg, max) = (3.721, 3.773, 3.809), stdev = 0.046
  CI (99.9%): [2.927, 4.619] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 8.447 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.806 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.297 ±(99.9%) 0.009 ms/op
Iteration   1: 3.308 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.329 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  15.743 ms/op
                 createUser·p0.9999: 20.840 ms/op
                 createUser·p1.00:   21.561 ms/op

Iteration   2: 3.227 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.102 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   4.190 ms/op
                 createUser·p0.99:   5.546 ms/op
                 createUser·p0.999:  15.647 ms/op
                 createUser·p0.9999: 24.879 ms/op
                 createUser·p1.00:   25.428 ms/op

Iteration   3: 3.250 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.354 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   4.026 ms/op
                 createUser·p0.99:   5.489 ms/op
                 createUser·p0.999:  16.482 ms/op
                 createUser·p0.9999: 22.320 ms/op
                 createUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294393
  mean =      3.261 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25273 
    [ 2.500,  5.000) = 262710 
    [ 5.000,  7.500) = 5564 
    [ 7.500, 10.000) = 335 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.102 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.121 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =     16.303 ms/op
     p(99.9900) =     23.579 ms/op
     p(99.9990) =     25.362 ms/op
     p(99.9999) =     25.428 ms/op
    p(100.0000) =     25.428 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 8.286 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.643 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.212 ±(99.9%) 0.008 ms/op
Iteration   1: 3.235 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.407 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   4.043 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  10.404 ms/op
                 existUser·p0.9999: 20.058 ms/op
                 existUser·p1.00:   21.201 ms/op

Iteration   2: 3.167 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.223 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   5.857 ms/op
                 existUser·p0.999:  12.105 ms/op
                 existUser·p0.9999: 23.065 ms/op
                 existUser·p1.00:   24.183 ms/op

Iteration   3: 3.212 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.274 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  15.926 ms/op
                 existUser·p0.9999: 22.386 ms/op
                 existUser·p1.00:   23.560 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 299374
  mean =      3.204 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27669 
    [ 2.500,  5.000) = 265642 
    [ 5.000,  7.500) = 5030 
    [ 7.500, 10.000) = 461 
    [10.000, 12.500) = 223 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 142 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.223 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     14.232 ms/op
     p(99.9900) =     22.483 ms/op
     p(99.9990) =     23.693 ms/op
     p(99.9999) =     24.183 ms/op
    p(100.0000) =     24.183 ms/op


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
# Warmup Iteration   1: 7.712 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.485 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.289 ±(99.9%) 0.011 ms/op
Iteration   1: 3.299 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.341 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   6.226 ms/op
                 getUser·p0.999:  11.715 ms/op
                 getUser·p0.9999: 20.578 ms/op
                 getUser·p1.00:   21.299 ms/op

Iteration   2: 3.287 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.159 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.754 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   5.925 ms/op
                 getUser·p0.999:  16.055 ms/op
                 getUser·p0.9999: 22.300 ms/op
                 getUser·p1.00:   23.036 ms/op

Iteration   3: 3.158 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.694 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.907 ms/op
                 getUser·p0.999:  10.502 ms/op
                 getUser·p0.9999: 21.197 ms/op
                 getUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295651
  mean =      3.247 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19986 
    [ 2.500,  5.000) = 269726 
    [ 5.000,  7.500) = 5056 
    [ 7.500, 10.000) = 514 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 144 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.159 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      4.076 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =     15.898 ms/op
     p(99.9900) =     21.182 ms/op
     p(99.9990) =     22.876 ms/op
     p(99.9999) =     23.036 ms/op
    p(100.0000) =     23.036 ms/op


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
# Warmup Iteration   1: 10.166 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 4.194 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.784 ±(99.9%) 0.011 ms/op
Iteration   1: 3.860 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.522 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.190 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   7.897 ms/op
                 listUser·p0.999:  14.434 ms/op
                 listUser·p0.9999: 21.880 ms/op
                 listUser·p1.00:   22.675 ms/op

Iteration   2: 3.815 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.208 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  13.468 ms/op
                 listUser·p0.9999: 20.611 ms/op
                 listUser·p1.00:   20.677 ms/op

Iteration   3: 3.832 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.019 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.178 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   7.209 ms/op
                 listUser·p0.999:  13.503 ms/op
                 listUser·p0.9999: 15.477 ms/op
                 listUser·p1.00:   15.909 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 250115
  mean =      3.836 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48 
    [ 2.500,  5.000) = 241703 
    [ 5.000,  7.500) = 6055 
    [ 7.500, 10.000) = 1533 
    [10.000, 12.500) = 314 
    [12.500, 15.000) = 338 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.522 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      7.406 ms/op
     p(99.9000) =     13.662 ms/op
     p(99.9900) =     20.676 ms/op
     p(99.9990) =     22.397 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.811 ± 0.820  ops/ms
ClientPb.existUser                       thrpt       3  10.018 ± 3.831  ops/ms
ClientPb.getUser                         thrpt       3   9.956 ± 2.754  ops/ms
ClientPb.listUser                        thrpt       3   8.482 ± 1.239  ops/ms
ClientPb.createUser                       avgt       3   3.238 ± 0.965   ms/op
ClientPb.existUser                        avgt       3   3.110 ± 1.568   ms/op
ClientPb.getUser                          avgt       3   3.248 ± 0.593   ms/op
ClientPb.listUser                         avgt       3   3.773 ± 0.846   ms/op
ClientPb.createUser                     sample  294393   3.261 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.102           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.752           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.121           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.587           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.303           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.579           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.428           ms/op
ClientPb.existUser                      sample  299374   3.204 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.223           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.166           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.539           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.875           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.603           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.232           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.483           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.183           ms/op
ClientPb.getUser                        sample  295651   3.247 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.159           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.723           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.076           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.767           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.898           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.182           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.036           ms/op
ClientPb.listUser                       sample  250115   3.836 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.522           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.727           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.190           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.406           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.662           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.676           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.675           ms/op
