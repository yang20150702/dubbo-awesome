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
# Warmup Iteration   1: 2.694 ops/ms
# Warmup Iteration   2: 6.243 ops/ms
# Warmup Iteration   3: 9.122 ops/ms
Iteration   1: 9.744 ops/ms
Iteration   2: 9.934 ops/ms
Iteration   3: 9.580 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.753 ±(99.9%) 3.230 ops/ms [Average]
  (min, avg, max) = (9.580, 9.753, 9.934), stdev = 0.177
  CI (99.9%): [6.523, 12.983] (assumes normal distribution)


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
# Warmup Iteration   1: 3.677 ops/ms
# Warmup Iteration   2: 9.406 ops/ms
# Warmup Iteration   3: 10.243 ops/ms
Iteration   1: 10.274 ops/ms
Iteration   2: 9.983 ops/ms
Iteration   3: 10.458 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.238 ±(99.9%) 4.374 ops/ms [Average]
  (min, avg, max) = (9.983, 10.238, 10.458), stdev = 0.240
  CI (99.9%): [5.865, 14.612] (assumes normal distribution)


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
# Warmup Iteration   1: 3.218 ops/ms
# Warmup Iteration   2: 9.374 ops/ms
# Warmup Iteration   3: 9.814 ops/ms
Iteration   1: 10.143 ops/ms
Iteration   2: 10.309 ops/ms
Iteration   3: 10.313 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.255 ±(99.9%) 1.773 ops/ms [Average]
  (min, avg, max) = (10.143, 10.255, 10.313), stdev = 0.097
  CI (99.9%): [8.482, 12.028] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.630 ops/ms
# Warmup Iteration   2: 7.887 ops/ms
# Warmup Iteration   3: 8.403 ops/ms
Iteration   1: 8.482 ops/ms
Iteration   2: 8.725 ops/ms
Iteration   3: 8.464 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.557 ±(99.9%) 2.656 ops/ms [Average]
  (min, avg, max) = (8.464, 8.557, 8.725), stdev = 0.146
  CI (99.9%): [5.901, 11.213] (assumes normal distribution)


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
# Warmup Iteration   1: 7.691 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.561 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.240 ±(99.9%) 0.002 ms/op
Iteration   1: 3.136 ±(99.9%) 0.006 ms/op
Iteration   2: 3.201 ±(99.9%) 0.003 ms/op
Iteration   3: 3.236 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.191 ±(99.9%) 0.927 ms/op [Average]
  (min, avg, max) = (3.136, 3.191, 3.236), stdev = 0.051
  CI (99.9%): [2.264, 4.117] (assumes normal distribution)


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
# Warmup Iteration   1: 7.163 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.218 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.148 ±(99.9%) 0.006 ms/op
Iteration   1: 3.071 ±(99.9%) 0.003 ms/op
Iteration   2: 3.033 ±(99.9%) 0.007 ms/op
Iteration   3: 3.097 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.067 ±(99.9%) 0.586 ms/op [Average]
  (min, avg, max) = (3.033, 3.067, 3.097), stdev = 0.032
  CI (99.9%): [2.481, 3.653] (assumes normal distribution)


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
# Warmup Iteration   1: 7.123 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.566 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.337 ±(99.9%) 0.004 ms/op
Iteration   1: 3.236 ±(99.9%) 0.006 ms/op
Iteration   2: 3.102 ±(99.9%) 0.004 ms/op
Iteration   3: 3.105 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.148 ±(99.9%) 1.394 ms/op [Average]
  (min, avg, max) = (3.102, 3.148, 3.236), stdev = 0.076
  CI (99.9%): [1.754, 4.541] (assumes normal distribution)


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
# Warmup Iteration   1: 8.852 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.041 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.759 ±(99.9%) 0.008 ms/op
Iteration   1: 3.676 ±(99.9%) 0.009 ms/op
Iteration   2: 3.727 ±(99.9%) 0.007 ms/op
Iteration   3: 3.878 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.760 ±(99.9%) 1.912 ms/op [Average]
  (min, avg, max) = (3.676, 3.760, 3.878), stdev = 0.105
  CI (99.9%): [1.848, 5.672] (assumes normal distribution)


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
# Warmup Iteration   1: 7.705 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.690 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.100 ±(99.9%) 0.008 ms/op
Iteration   1: 3.119 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.895 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.686 ms/op
                 createUser·p0.99:   5.366 ms/op
                 createUser·p0.999:  9.199 ms/op
                 createUser·p0.9999: 22.307 ms/op
                 createUser·p1.00:   22.774 ms/op

Iteration   2: 3.137 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.499 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   5.341 ms/op
                 createUser·p0.999:  18.581 ms/op
                 createUser·p0.9999: 21.752 ms/op
                 createUser·p1.00:   22.381 ms/op

Iteration   3: 3.326 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.422 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   5.685 ms/op
                 createUser·p0.999:  15.429 ms/op
                 createUser·p0.9999: 18.026 ms/op
                 createUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300749
  mean =      3.191 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19368 
    [ 2.500,  5.000) = 275880 
    [ 5.000,  7.500) = 4849 
    [ 7.500, 10.000) = 206 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 139 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.422 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      5.419 ms/op
     p(99.9000) =     16.400 ms/op
     p(99.9900) =     21.624 ms/op
     p(99.9990) =     22.675 ms/op
     p(99.9999) =     22.774 ms/op
    p(100.0000) =     22.774 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.027 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.330 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.096 ±(99.9%) 0.008 ms/op
Iteration   1: 3.033 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.217 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.174 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   5.251 ms/op
                 existUser·p0.999:  9.208 ms/op
                 existUser·p0.9999: 21.070 ms/op
                 existUser·p1.00:   21.561 ms/op

Iteration   2: 3.010 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.847 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.203 ms/op
                 existUser·p0.95:   3.379 ms/op
                 existUser·p0.99:   5.086 ms/op
                 existUser·p0.999:  13.046 ms/op
                 existUser·p0.9999: 22.053 ms/op
                 existUser·p1.00:   23.265 ms/op

Iteration   3: 3.082 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.217 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   5.308 ms/op
                 existUser·p0.999:  13.533 ms/op
                 existUser·p0.9999: 20.501 ms/op
                 existUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 315395
  mean =      3.042 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10864 
    [ 2.500,  5.000) = 300010 
    [ 5.000,  7.500) = 3815 
    [ 7.500, 10.000) = 297 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 151 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.847 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.240 ms/op
     p(95.0000) =      3.465 ms/op
     p(99.0000) =      5.259 ms/op
     p(99.9000) =     13.055 ms/op
     p(99.9900) =     21.266 ms/op
     p(99.9990) =     23.233 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


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
# Warmup Iteration   1: 7.489 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.414 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.450 ±(99.9%) 0.011 ms/op
Iteration   1: 3.163 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.331 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.420 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   5.898 ms/op
                 getUser·p0.999:  21.117 ms/op
                 getUser·p0.9999: 27.223 ms/op
                 getUser·p1.00:   28.934 ms/op

Iteration   2: 3.198 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.282 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   5.710 ms/op
                 getUser·p0.999:  13.373 ms/op
                 getUser·p0.9999: 23.266 ms/op
                 getUser·p1.00:   24.314 ms/op

Iteration   3: 3.174 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.990 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   5.661 ms/op
                 getUser·p0.999:  14.877 ms/op
                 getUser·p0.9999: 33.126 ms/op
                 getUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 301878
  mean =      3.178 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13273 
    [ 2.500,  5.000) = 282915 
    [ 5.000,  7.500) = 4596 
    [ 7.500, 10.000) = 611 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.990 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     15.964 ms/op
     p(99.9900) =     31.658 ms/op
     p(99.9990) =     33.324 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


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
# Warmup Iteration   1: 9.597 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 4.142 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.801 ±(99.9%) 0.012 ms/op
Iteration   1: 3.779 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.819 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   7.101 ms/op
                 listUser·p0.999:  14.762 ms/op
                 listUser·p0.9999: 20.417 ms/op
                 listUser·p1.00:   21.627 ms/op

Iteration   2: 3.746 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   3.609 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   7.161 ms/op
                 listUser·p0.999:  15.270 ms/op
                 listUser·p0.9999: 21.000 ms/op
                 listUser·p1.00:   21.823 ms/op

Iteration   3: 3.870 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  14.485 ms/op
                 listUser·p0.9999: 17.269 ms/op
                 listUser·p1.00:   17.433 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252650
  mean =      3.798 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 91 
    [ 2.500,  5.000) = 243134 
    [ 5.000,  7.500) = 7691 
    [ 7.500, 10.000) = 1071 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 257 
    [15.000, 17.500) = 165 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.819 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.178 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     14.866 ms/op
     p(99.9900) =     19.637 ms/op
     p(99.9990) =     21.791 ms/op
     p(99.9999) =     21.823 ms/op
    p(100.0000) =     21.823 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.753 ± 3.230  ops/ms
ClientPb.existUser                       thrpt       3  10.238 ± 4.374  ops/ms
ClientPb.getUser                         thrpt       3  10.255 ± 1.773  ops/ms
ClientPb.listUser                        thrpt       3   8.557 ± 2.656  ops/ms
ClientPb.createUser                       avgt       3   3.191 ± 0.927   ms/op
ClientPb.existUser                        avgt       3   3.067 ± 0.586   ms/op
ClientPb.getUser                          avgt       3   3.148 ± 1.394   ms/op
ClientPb.listUser                         avgt       3   3.760 ± 1.912   ms/op
ClientPb.createUser                     sample  300749   3.191 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.422           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.564           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.850           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.419           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.400           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.624           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.774           ms/op
ClientPb.existUser                      sample  315395   3.042 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.847           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.949           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.240           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.465           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.259           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.055           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.266           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.265           ms/op
ClientPb.getUser                        sample  301878   3.178 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.990           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.490           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.727           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.702           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.964           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.658           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.751           ms/op
ClientPb.listUser                       sample  252650   3.798 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.819           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.682           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.178           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.914           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.866           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.637           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.823           ms/op
