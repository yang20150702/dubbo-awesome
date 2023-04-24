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
# Warmup Iteration   1: 1.549 ops/ms
# Warmup Iteration   2: 3.622 ops/ms
# Warmup Iteration   3: 7.136 ops/ms
Iteration   1: 6.941 ops/ms
Iteration   2: 7.819 ops/ms
Iteration   3: 8.325 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.695 ±(99.9%) 12.778 ops/ms [Average]
  (min, avg, max) = (6.941, 7.695, 8.325), stdev = 0.700
  CI (99.9%): [≈ 0, 20.473] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.181 ops/ms
# Warmup Iteration   2: 7.069 ops/ms
# Warmup Iteration   3: 7.694 ops/ms
Iteration   1: 8.353 ops/ms
Iteration   2: 8.221 ops/ms
Iteration   3: 8.427 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.334 ±(99.9%) 1.905 ops/ms [Average]
  (min, avg, max) = (8.221, 8.334, 8.427), stdev = 0.104
  CI (99.9%): [6.429, 10.239] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.128 ops/ms
# Warmup Iteration   2: 6.818 ops/ms
# Warmup Iteration   3: 7.793 ops/ms
Iteration   1: 7.409 ops/ms
Iteration   2: 7.579 ops/ms
Iteration   3: 7.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.594 ±(99.9%) 3.511 ops/ms [Average]
  (min, avg, max) = (7.409, 7.594, 7.793), stdev = 0.192
  CI (99.9%): [4.083, 11.105] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.933 ops/ms
# Warmup Iteration   2: 4.579 ops/ms
# Warmup Iteration   3: 6.664 ops/ms
Iteration   1: 6.294 ops/ms
Iteration   2: 6.061 ops/ms
Iteration   3: 6.649 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.335 ±(99.9%) 5.401 ops/ms [Average]
  (min, avg, max) = (6.061, 6.335, 6.649), stdev = 0.296
  CI (99.9%): [0.934, 11.736] (assumes normal distribution)


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
# Warmup Iteration   1: 13.425 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 5.122 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.301 ±(99.9%) 0.007 ms/op
Iteration   1: 4.278 ±(99.9%) 0.003 ms/op
Iteration   2: 3.946 ±(99.9%) 0.008 ms/op
Iteration   3: 4.000 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.075 ±(99.9%) 3.260 ms/op [Average]
  (min, avg, max) = (3.946, 4.075, 4.278), stdev = 0.179
  CI (99.9%): [0.815, 7.334] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 12.655 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.447 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.918 ±(99.9%) 0.005 ms/op
Iteration   1: 3.749 ±(99.9%) 0.009 ms/op
Iteration   2: 3.855 ±(99.9%) 0.006 ms/op
Iteration   3: 3.838 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.814 ±(99.9%) 1.035 ms/op [Average]
  (min, avg, max) = (3.749, 3.814, 3.855), stdev = 0.057
  CI (99.9%): [2.779, 4.849] (assumes normal distribution)


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
# Warmup Iteration   1: 10.146 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 6.150 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.314 ±(99.9%) 0.006 ms/op
Iteration   1: 4.346 ±(99.9%) 0.009 ms/op
Iteration   2: 3.911 ±(99.9%) 0.014 ms/op
Iteration   3: 3.962 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.073 ±(99.9%) 4.332 ms/op [Average]
  (min, avg, max) = (3.911, 4.073, 4.346), stdev = 0.237
  CI (99.9%): [≈ 0, 8.405] (assumes normal distribution)


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
# Warmup Iteration   1: 15.544 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.633 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.744 ±(99.9%) 0.013 ms/op
Iteration   1: 4.758 ±(99.9%) 0.011 ms/op
Iteration   2: 4.596 ±(99.9%) 0.015 ms/op
Iteration   3: 4.658 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.671 ±(99.9%) 1.490 ms/op [Average]
  (min, avg, max) = (4.596, 4.671, 4.758), stdev = 0.082
  CI (99.9%): [3.181, 6.161] (assumes normal distribution)


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
# Warmup Iteration   1: 14.514 ±(99.9%) 0.192 ms/op
# Warmup Iteration   2: 5.811 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 4.380 ±(99.9%) 0.018 ms/op
Iteration   1: 4.099 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.772 ms/op
                 createUser·p0.50:   3.908 ms/op
                 createUser·p0.90:   4.833 ms/op
                 createUser·p0.95:   5.513 ms/op
                 createUser·p0.99:   8.159 ms/op
                 createUser·p0.999:  23.935 ms/op
                 createUser·p0.9999: 26.810 ms/op
                 createUser·p1.00:   28.901 ms/op

Iteration   2: 4.105 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.831 ms/op
                 createUser·p0.50:   3.899 ms/op
                 createUser·p0.90:   4.719 ms/op
                 createUser·p0.95:   5.186 ms/op
                 createUser·p0.99:   7.635 ms/op
                 createUser·p0.999:  20.842 ms/op
                 createUser·p0.9999: 29.636 ms/op
                 createUser·p1.00:   30.671 ms/op

Iteration   3: 4.017 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.087 ms/op
                 createUser·p0.50:   3.781 ms/op
                 createUser·p0.90:   4.473 ms/op
                 createUser·p0.95:   5.014 ms/op
                 createUser·p0.99:   8.315 ms/op
                 createUser·p0.999:  27.558 ms/op
                 createUser·p0.9999: 31.166 ms/op
                 createUser·p1.00:   32.244 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 235596
  mean =      4.074 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 201 
    [ 2.500,  5.000) = 220077 
    [ 5.000,  7.500) = 12170 
    [ 7.500, 10.000) = 2091 
    [10.000, 12.500) = 528 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 110 
    [27.500, 30.000) = 106 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.772 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.284 ms/op
     p(99.0000) =      8.036 ms/op
     p(99.9000) =     25.179 ms/op
     p(99.9900) =     30.299 ms/op
     p(99.9990) =     31.509 ms/op
     p(99.9999) =     32.244 ms/op
    p(100.0000) =     32.244 ms/op


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
# Warmup Iteration   1: 13.890 ±(99.9%) 0.242 ms/op
# Warmup Iteration   2: 4.785 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.382 ±(99.9%) 0.016 ms/op
Iteration   1: 4.282 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.499 ms/op
                 existUser·p0.50:   3.998 ms/op
                 existUser·p0.90:   5.222 ms/op
                 existUser·p0.95:   6.529 ms/op
                 existUser·p0.99:   8.917 ms/op
                 existUser·p0.999:  19.497 ms/op
                 existUser·p0.9999: 26.134 ms/op
                 existUser·p1.00:   26.870 ms/op

Iteration   2: 3.825 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   2.327 ms/op
                 existUser·p0.50:   3.756 ms/op
                 existUser·p0.90:   4.026 ms/op
                 existUser·p0.95:   4.317 ms/op
                 existUser·p0.99:   6.504 ms/op
                 existUser·p0.999:  10.437 ms/op
                 existUser·p0.9999: 27.448 ms/op
                 existUser·p1.00:   29.262 ms/op

Iteration   3: 4.111 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.455 ms/op
                 existUser·p0.50:   3.895 ms/op
                 existUser·p0.90:   4.760 ms/op
                 existUser·p0.95:   5.538 ms/op
                 existUser·p0.99:   7.832 ms/op
                 existUser·p0.999:  29.065 ms/op
                 existUser·p0.9999: 31.519 ms/op
                 existUser·p1.00:   32.899 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 236108
  mean =      4.064 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 156 
    [ 2.500,  5.000) = 219092 
    [ 5.000,  7.500) = 13699 
    [ 7.500, 10.000) = 2193 
    [10.000, 12.500) = 591 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 85 
    [27.500, 30.000) = 67 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.455 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.661 ms/op
     p(95.0000) =      5.480 ms/op
     p(99.0000) =      7.946 ms/op
     p(99.9000) =     19.464 ms/op
     p(99.9900) =     30.802 ms/op
     p(99.9990) =     32.533 ms/op
     p(99.9999) =     32.899 ms/op
    p(100.0000) =     32.899 ms/op


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
# Warmup Iteration   1: 14.227 ±(99.9%) 0.191 ms/op
# Warmup Iteration   2: 5.071 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.465 ±(99.9%) 0.020 ms/op
Iteration   1: 4.138 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.138 ms/op
                 getUser·p0.50:   3.863 ms/op
                 getUser·p0.90:   4.653 ms/op
                 getUser·p0.95:   5.579 ms/op
                 getUser·p0.99:   9.077 ms/op
                 getUser·p0.999:  24.183 ms/op
                 getUser·p0.9999: 25.887 ms/op
                 getUser·p1.00:   27.460 ms/op

Iteration   2: 4.353 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.228 ms/op
                 getUser·p0.50:   4.063 ms/op
                 getUser·p0.90:   5.513 ms/op
                 getUser·p0.95:   6.291 ms/op
                 getUser·p0.99:   8.323 ms/op
                 getUser·p0.999:  27.318 ms/op
                 getUser·p0.9999: 33.052 ms/op
                 getUser·p1.00:   33.456 ms/op

Iteration   3: 4.180 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.253 ms/op
                 getUser·p0.50:   3.977 ms/op
                 getUser·p0.90:   4.841 ms/op
                 getUser·p0.95:   5.718 ms/op
                 getUser·p0.99:   8.045 ms/op
                 getUser·p0.999:  13.034 ms/op
                 getUser·p0.9999: 32.583 ms/op
                 getUser·p1.00:   33.620 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 227192
  mean =      4.222 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 63 
    [ 2.500,  5.000) = 204903 
    [ 5.000,  7.500) = 18103 
    [ 7.500, 10.000) = 3139 
    [10.000, 12.500) = 532 
    [12.500, 15.000) = 146 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 59 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.138 ms/op
     p(50.0000) =      3.973 ms/op
     p(90.0000) =      4.981 ms/op
     p(95.0000) =      5.972 ms/op
     p(99.0000) =      8.454 ms/op
     p(99.9000) =     24.347 ms/op
     p(99.9900) =     32.524 ms/op
     p(99.9990) =     33.438 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


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
# Warmup Iteration   1: 16.089 ±(99.9%) 0.237 ms/op
# Warmup Iteration   2: 5.877 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.896 ±(99.9%) 0.019 ms/op
Iteration   1: 4.732 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.249 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   8.225 ms/op
                 listUser·p0.999:  25.220 ms/op
                 listUser·p0.9999: 26.746 ms/op
                 listUser·p1.00:   28.312 ms/op

Iteration   2: 4.779 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.675 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   8.411 ms/op
                 listUser·p0.999:  18.944 ms/op
                 listUser·p0.9999: 25.217 ms/op
                 listUser·p1.00:   27.001 ms/op

Iteration   3: 4.907 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.343 ms/op
                 listUser·p0.50:   4.694 ms/op
                 listUser·p0.90:   5.472 ms/op
                 listUser·p0.95:   6.472 ms/op
                 listUser·p0.99:   9.060 ms/op
                 listUser·p0.999:  18.114 ms/op
                 listUser·p0.9999: 24.608 ms/op
                 listUser·p1.00:   25.428 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 199609
  mean =      4.805 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 160024 
    [ 5.000,  7.500) = 34987 
    [ 7.500, 10.000) = 3584 
    [10.000, 12.500) = 390 
    [12.500, 15.000) = 167 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 86 

  Percentiles, ms/op:
      p(0.0000) =      2.249 ms/op
     p(50.0000) =      4.612 ms/op
     p(90.0000) =      5.284 ms/op
     p(95.0000) =      5.833 ms/op
     p(99.0000) =      8.569 ms/op
     p(99.9000) =     22.239 ms/op
     p(99.9900) =     26.345 ms/op
     p(99.9990) =     27.985 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   7.695 ± 12.778  ops/ms
ClientPb.existUser                       thrpt       3   8.334 ±  1.905  ops/ms
ClientPb.getUser                         thrpt       3   7.594 ±  3.511  ops/ms
ClientPb.listUser                        thrpt       3   6.335 ±  5.401  ops/ms
ClientPb.createUser                       avgt       3   4.075 ±  3.260   ms/op
ClientPb.existUser                        avgt       3   3.814 ±  1.035   ms/op
ClientPb.getUser                          avgt       3   4.073 ±  4.332   ms/op
ClientPb.listUser                         avgt       3   4.671 ±  1.490   ms/op
ClientPb.createUser                     sample  235596   4.074 ±  0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.772            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.871            ms/op
ClientPb.createUser:createUser·p0.90    sample           4.669            ms/op
ClientPb.createUser:createUser·p0.95    sample           5.284            ms/op
ClientPb.createUser:createUser·p0.99    sample           8.036            ms/op
ClientPb.createUser:createUser·p0.999   sample          25.179            ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.299            ms/op
ClientPb.createUser:createUser·p1.00    sample          32.244            ms/op
ClientPb.existUser                      sample  236108   4.064 ±  0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.455            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.883            ms/op
ClientPb.existUser:existUser·p0.90      sample           4.661            ms/op
ClientPb.existUser:existUser·p0.95      sample           5.480            ms/op
ClientPb.existUser:existUser·p0.99      sample           7.946            ms/op
ClientPb.existUser:existUser·p0.999     sample          19.464            ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.802            ms/op
ClientPb.existUser:existUser·p1.00      sample          32.899            ms/op
ClientPb.getUser                        sample  227192   4.222 ±  0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.138            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.973            ms/op
ClientPb.getUser:getUser·p0.90          sample           4.981            ms/op
ClientPb.getUser:getUser·p0.95          sample           5.972            ms/op
ClientPb.getUser:getUser·p0.99          sample           8.454            ms/op
ClientPb.getUser:getUser·p0.999         sample          24.347            ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.524            ms/op
ClientPb.getUser:getUser·p1.00          sample          33.620            ms/op
ClientPb.listUser                       sample  199609   4.805 ±  0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.249            ms/op
ClientPb.listUser:listUser·p0.50        sample           4.612            ms/op
ClientPb.listUser:listUser·p0.90        sample           5.284            ms/op
ClientPb.listUser:listUser·p0.95        sample           5.833            ms/op
ClientPb.listUser:listUser·p0.99        sample           8.569            ms/op
ClientPb.listUser:listUser·p0.999       sample          22.239            ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.345            ms/op
ClientPb.listUser:listUser·p1.00        sample          28.312            ms/op
