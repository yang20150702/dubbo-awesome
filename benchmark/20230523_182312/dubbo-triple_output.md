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
# Warmup Iteration   1: 2.055 ops/ms
# Warmup Iteration   2: 5.923 ops/ms
# Warmup Iteration   3: 8.490 ops/ms
Iteration   1: 9.342 ops/ms
Iteration   2: 9.465 ops/ms
Iteration   3: 9.649 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.485 ±(99.9%) 2.814 ops/ms [Average]
  (min, avg, max) = (9.342, 9.485, 9.649), stdev = 0.154
  CI (99.9%): [6.672, 12.299] (assumes normal distribution)


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
# Warmup Iteration   1: 3.907 ops/ms
# Warmup Iteration   2: 8.973 ops/ms
# Warmup Iteration   3: 9.650 ops/ms
Iteration   1: 10.034 ops/ms
Iteration   2: 9.971 ops/ms
Iteration   3: 9.816 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.940 ±(99.9%) 2.051 ops/ms [Average]
  (min, avg, max) = (9.816, 9.940, 10.034), stdev = 0.112
  CI (99.9%): [7.889, 11.991] (assumes normal distribution)


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
# Warmup Iteration   1: 3.235 ops/ms
# Warmup Iteration   2: 8.719 ops/ms
# Warmup Iteration   3: 9.042 ops/ms
Iteration   1: 9.318 ops/ms
Iteration   2: 9.491 ops/ms
Iteration   3: 9.223 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.344 ±(99.9%) 2.474 ops/ms [Average]
  (min, avg, max) = (9.223, 9.344, 9.491), stdev = 0.136
  CI (99.9%): [6.870, 11.818] (assumes normal distribution)


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
# Warmup Iteration   1: 2.858 ops/ms
# Warmup Iteration   2: 7.284 ops/ms
# Warmup Iteration   3: 7.715 ops/ms
Iteration   1: 8.136 ops/ms
Iteration   2: 7.927 ops/ms
Iteration   3: 8.170 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.078 ±(99.9%) 2.398 ops/ms [Average]
  (min, avg, max) = (7.927, 8.078, 8.170), stdev = 0.131
  CI (99.9%): [5.680, 10.476] (assumes normal distribution)


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
# Warmup Iteration   1: 9.296 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.738 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.529 ±(99.9%) 0.006 ms/op
Iteration   1: 3.444 ±(99.9%) 0.004 ms/op
Iteration   2: 3.440 ±(99.9%) 0.009 ms/op
Iteration   3: 3.662 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.515 ±(99.9%) 2.319 ms/op [Average]
  (min, avg, max) = (3.440, 3.515, 3.662), stdev = 0.127
  CI (99.9%): [1.196, 5.834] (assumes normal distribution)


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
# Warmup Iteration   1: 8.059 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.629 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.353 ±(99.9%) 0.010 ms/op
Iteration   1: 3.220 ±(99.9%) 0.005 ms/op
Iteration   2: 3.207 ±(99.9%) 0.009 ms/op
Iteration   3: 3.168 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.199 ±(99.9%) 0.496 ms/op [Average]
  (min, avg, max) = (3.168, 3.199, 3.220), stdev = 0.027
  CI (99.9%): [2.703, 3.694] (assumes normal distribution)


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
# Warmup Iteration   1: 8.511 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.647 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.530 ±(99.9%) 0.003 ms/op
Iteration   1: 3.317 ±(99.9%) 0.009 ms/op
Iteration   2: 3.445 ±(99.9%) 0.004 ms/op
Iteration   3: 3.427 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.397 ±(99.9%) 1.263 ms/op [Average]
  (min, avg, max) = (3.317, 3.397, 3.445), stdev = 0.069
  CI (99.9%): [2.133, 4.660] (assumes normal distribution)


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
# Warmup Iteration   1: 11.300 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.348 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.081 ±(99.9%) 0.010 ms/op
Iteration   1: 3.919 ±(99.9%) 0.013 ms/op
Iteration   2: 3.950 ±(99.9%) 0.010 ms/op
Iteration   3: 3.939 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.936 ±(99.9%) 0.287 ms/op [Average]
  (min, avg, max) = (3.919, 3.936, 3.950), stdev = 0.016
  CI (99.9%): [3.649, 4.223] (assumes normal distribution)


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
# Warmup Iteration   1: 9.784 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.007 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.481 ±(99.9%) 0.010 ms/op
Iteration   1: 3.465 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.223 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   4.022 ms/op
                 createUser·p0.95:   4.489 ms/op
                 createUser·p0.99:   5.972 ms/op
                 createUser·p0.999:  21.345 ms/op
                 createUser·p0.9999: 25.733 ms/op
                 createUser·p1.00:   26.182 ms/op

Iteration   2: 3.464 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.237 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   3.936 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   5.767 ms/op
                 createUser·p0.999:  21.365 ms/op
                 createUser·p0.9999: 27.298 ms/op
                 createUser·p1.00:   27.853 ms/op

Iteration   3: 3.354 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.534 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  19.155 ms/op
                 createUser·p0.9999: 28.746 ms/op
                 createUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280004
  mean =      3.427 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6333 
    [ 2.500,  5.000) = 265952 
    [ 5.000,  7.500) = 6893 
    [ 7.500, 10.000) = 372 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 106 

  Percentiles, ms/op:
      p(0.0000) =      1.223 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     19.759 ms/op
     p(99.9900) =     27.066 ms/op
     p(99.9990) =     29.255 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


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
# Warmup Iteration   1: 8.712 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.609 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.419 ±(99.9%) 0.008 ms/op
Iteration   1: 3.283 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.135 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   5.292 ms/op
                 existUser·p0.999:  9.683 ms/op
                 existUser·p0.9999: 21.889 ms/op
                 existUser·p1.00:   22.249 ms/op

Iteration   2: 3.347 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.910 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.838 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  19.368 ms/op
                 existUser·p0.9999: 24.740 ms/op
                 existUser·p1.00:   25.264 ms/op

Iteration   3: 3.362 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.212 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   4.116 ms/op
                 existUser·p0.99:   6.414 ms/op
                 existUser·p0.999:  16.842 ms/op
                 existUser·p0.9999: 24.461 ms/op
                 existUser·p1.00:   25.231 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288009
  mean =      3.330 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13225 
    [ 2.500,  5.000) = 269207 
    [ 5.000,  7.500) = 4944 
    [ 7.500, 10.000) = 354 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.910 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      4.067 ms/op
     p(99.0000) =      5.947 ms/op
     p(99.9000) =      9.847 ms/op
     p(99.9900) =     24.386 ms/op
     p(99.9990) =     25.174 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


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
# Warmup Iteration   1: 9.295 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.855 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.574 ±(99.9%) 0.012 ms/op
Iteration   1: 3.517 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.108 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   4.137 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   5.825 ms/op
                 getUser·p0.999:  20.611 ms/op
                 getUser·p0.9999: 22.839 ms/op
                 getUser·p1.00:   23.757 ms/op

Iteration   2: 3.541 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.737 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   4.149 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   6.504 ms/op
                 getUser·p0.999:  11.485 ms/op
                 getUser·p0.9999: 25.198 ms/op
                 getUser·p1.00:   27.394 ms/op

Iteration   3: 3.422 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.561 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   4.178 ms/op
                 getUser·p0.99:   6.472 ms/op
                 getUser·p0.999:  19.806 ms/op
                 getUser·p0.9999: 30.048 ms/op
                 getUser·p1.00:   30.573 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274683
  mean =      3.493 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12799 
    [ 2.500,  5.000) = 252075 
    [ 5.000,  7.500) = 8570 
    [ 7.500, 10.000) = 792 
    [10.000, 12.500) = 164 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.108 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      4.059 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      6.283 ms/op
     p(99.9000) =     12.631 ms/op
     p(99.9900) =     28.738 ms/op
     p(99.9990) =     30.540 ms/op
     p(99.9999) =     30.573 ms/op
    p(100.0000) =     30.573 ms/op


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
# Warmup Iteration   1: 10.501 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.537 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.136 ±(99.9%) 0.014 ms/op
Iteration   1: 4.019 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.602 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   7.791 ms/op
                 listUser·p0.999:  20.513 ms/op
                 listUser·p0.9999: 24.712 ms/op
                 listUser·p1.00:   25.100 ms/op

Iteration   2: 4.014 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.612 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   7.347 ms/op
                 listUser·p0.999:  16.503 ms/op
                 listUser·p0.9999: 18.548 ms/op
                 listUser·p1.00:   21.692 ms/op

Iteration   3: 3.927 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.580 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   6.496 ms/op
                 listUser·p0.999:  14.877 ms/op
                 listUser·p0.9999: 16.695 ms/op
                 listUser·p1.00:   16.810 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240756
  mean =      3.986 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 232877 
    [ 5.000,  7.500) = 5593 
    [ 7.500, 10.000) = 1453 
    [10.000, 12.500) = 258 
    [12.500, 15.000) = 214 
    [15.000, 17.500) = 182 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.602 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      7.340 ms/op
     p(99.9000) =     16.133 ms/op
     p(99.9900) =     23.096 ms/op
     p(99.9990) =     24.989 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.485 ± 2.814  ops/ms
ClientPb.existUser                       thrpt       3   9.940 ± 2.051  ops/ms
ClientPb.getUser                         thrpt       3   9.344 ± 2.474  ops/ms
ClientPb.listUser                        thrpt       3   8.078 ± 2.398  ops/ms
ClientPb.createUser                       avgt       3   3.515 ± 2.319   ms/op
ClientPb.existUser                        avgt       3   3.199 ± 0.496   ms/op
ClientPb.getUser                          avgt       3   3.397 ± 1.263   ms/op
ClientPb.listUser                         avgt       3   3.936 ± 0.287   ms/op
ClientPb.createUser                     sample  280004   3.427 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.223           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.297           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.891           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.243           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.825           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.759           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.066           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.655           ms/op
ClientPb.existUser                      sample  288009   3.330 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.910           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.252           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.723           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.067           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.947           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.847           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.386           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.264           ms/op
ClientPb.getUser                        sample  274683   3.493 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.108           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.338           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.059           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.497           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.283           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.631           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.738           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.573           ms/op
ClientPb.listUser                       sample  240756   3.986 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.602           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.620           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.340           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.133           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.096           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.100           ms/op
