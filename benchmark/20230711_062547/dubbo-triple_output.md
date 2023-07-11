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
# Warmup Iteration   1: 2.112 ops/ms
# Warmup Iteration   2: 6.271 ops/ms
# Warmup Iteration   3: 8.606 ops/ms
Iteration   1: 9.285 ops/ms
Iteration   2: 8.964 ops/ms
Iteration   3: 9.694 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.314 ±(99.9%) 6.674 ops/ms [Average]
  (min, avg, max) = (8.964, 9.314, 9.694), stdev = 0.366
  CI (99.9%): [2.640, 15.988] (assumes normal distribution)


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
# Warmup Iteration   1: 2.919 ops/ms
# Warmup Iteration   2: 8.624 ops/ms
# Warmup Iteration   3: 9.190 ops/ms
Iteration   1: 9.651 ops/ms
Iteration   2: 9.833 ops/ms
Iteration   3: 9.852 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.779 ±(99.9%) 2.027 ops/ms [Average]
  (min, avg, max) = (9.651, 9.779, 9.852), stdev = 0.111
  CI (99.9%): [7.752, 11.806] (assumes normal distribution)


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
# Warmup Iteration   1: 3.086 ops/ms
# Warmup Iteration   2: 8.398 ops/ms
# Warmup Iteration   3: 8.960 ops/ms
Iteration   1: 9.338 ops/ms
Iteration   2: 9.527 ops/ms
Iteration   3: 9.502 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.455 ±(99.9%) 1.875 ops/ms [Average]
  (min, avg, max) = (9.338, 9.455, 9.527), stdev = 0.103
  CI (99.9%): [7.580, 11.330] (assumes normal distribution)


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
# Warmup Iteration   1: 2.693 ops/ms
# Warmup Iteration   2: 6.678 ops/ms
# Warmup Iteration   3: 7.769 ops/ms
Iteration   1: 7.722 ops/ms
Iteration   2: 7.860 ops/ms
Iteration   3: 7.960 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.847 ±(99.9%) 2.177 ops/ms [Average]
  (min, avg, max) = (7.722, 7.847, 7.960), stdev = 0.119
  CI (99.9%): [5.671, 10.024] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.668 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.756 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.469 ±(99.9%) 0.009 ms/op
Iteration   1: 3.442 ±(99.9%) 0.006 ms/op
Iteration   2: 3.385 ±(99.9%) 0.008 ms/op
Iteration   3: 3.360 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.396 ±(99.9%) 0.765 ms/op [Average]
  (min, avg, max) = (3.360, 3.396, 3.442), stdev = 0.042
  CI (99.9%): [2.631, 4.160] (assumes normal distribution)


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
# Warmup Iteration   1: 10.512 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.591 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.257 ±(99.9%) 0.009 ms/op
Iteration   1: 3.204 ±(99.9%) 0.008 ms/op
Iteration   2: 3.244 ±(99.9%) 0.005 ms/op
Iteration   3: 3.223 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.224 ±(99.9%) 0.358 ms/op [Average]
  (min, avg, max) = (3.204, 3.224, 3.244), stdev = 0.020
  CI (99.9%): [2.865, 3.582] (assumes normal distribution)


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
# Warmup Iteration   1: 9.123 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.530 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.419 ±(99.9%) 0.006 ms/op
Iteration   1: 3.497 ±(99.9%) 0.006 ms/op
Iteration   2: 3.444 ±(99.9%) 0.007 ms/op
Iteration   3: 3.350 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.430 ±(99.9%) 1.365 ms/op [Average]
  (min, avg, max) = (3.350, 3.430, 3.497), stdev = 0.075
  CI (99.9%): [2.065, 4.795] (assumes normal distribution)


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
# Warmup Iteration   1: 10.521 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.397 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.003 ±(99.9%) 0.007 ms/op
Iteration   1: 3.923 ±(99.9%) 0.013 ms/op
Iteration   2: 3.962 ±(99.9%) 0.009 ms/op
Iteration   3: 3.976 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.954 ±(99.9%) 0.509 ms/op [Average]
  (min, avg, max) = (3.923, 3.954, 3.976), stdev = 0.028
  CI (99.9%): [3.445, 4.463] (assumes normal distribution)


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
# Warmup Iteration   1: 11.091 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 3.976 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.648 ±(99.9%) 0.013 ms/op
Iteration   1: 3.443 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.651 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   6.865 ms/op
                 createUser·p0.999:  20.382 ms/op
                 createUser·p0.9999: 22.699 ms/op
                 createUser·p1.00:   24.052 ms/op

Iteration   2: 3.541 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.686 ms/op
                 createUser·p0.50:   3.453 ms/op
                 createUser·p0.90:   4.022 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   6.435 ms/op
                 createUser·p0.999:  21.266 ms/op
                 createUser·p0.9999: 25.230 ms/op
                 createUser·p1.00:   26.247 ms/op

Iteration   3: 3.468 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.417 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   3.920 ms/op
                 createUser·p0.95:   4.166 ms/op
                 createUser·p0.99:   5.800 ms/op
                 createUser·p0.999:  25.161 ms/op
                 createUser·p0.9999: 29.671 ms/op
                 createUser·p1.00:   30.409 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275324
  mean =      3.483 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6049 
    [ 2.500,  5.000) = 262605 
    [ 5.000,  7.500) = 5575 
    [ 7.500, 10.000) = 701 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.417 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.504 ms/op
     p(99.9000) =     20.600 ms/op
     p(99.9900) =     28.178 ms/op
     p(99.9990) =     30.310 ms/op
     p(99.9999) =     30.409 ms/op
    p(100.0000) =     30.409 ms/op


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
# Warmup Iteration   1: 8.966 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.752 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.332 ±(99.9%) 0.008 ms/op
Iteration   1: 3.206 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.200 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   5.145 ms/op
                 existUser·p0.999:  11.979 ms/op
                 existUser·p0.9999: 24.118 ms/op
                 existUser·p1.00:   24.838 ms/op

Iteration   2: 3.280 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.481 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.879 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  12.976 ms/op
                 existUser·p0.9999: 24.355 ms/op
                 existUser·p1.00:   25.723 ms/op

Iteration   3: 3.211 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.255 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   5.423 ms/op
                 existUser·p0.999:  9.202 ms/op
                 existUser·p0.9999: 27.558 ms/op
                 existUser·p1.00:   28.082 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 296623
  mean =      3.232 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15715 
    [ 2.500,  5.000) = 276655 
    [ 5.000,  7.500) = 3424 
    [ 7.500, 10.000) = 463 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 114 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      1.200 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =     12.960 ms/op
     p(99.9900) =     26.608 ms/op
     p(99.9990) =     27.918 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


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
# Warmup Iteration   1: 10.020 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.654 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.537 ±(99.9%) 0.009 ms/op
Iteration   1: 3.455 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.462 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   6.832 ms/op
                 getUser·p0.999:  19.864 ms/op
                 getUser·p0.9999: 25.330 ms/op
                 getUser·p1.00:   25.952 ms/op

Iteration   2: 3.357 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.876 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   5.380 ms/op
                 getUser·p0.999:  21.205 ms/op
                 getUser·p0.9999: 25.868 ms/op
                 getUser·p1.00:   26.444 ms/op

Iteration   3: 3.512 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.190 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   3.965 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   6.439 ms/op
                 getUser·p0.999:  20.742 ms/op
                 getUser·p0.9999: 24.638 ms/op
                 getUser·p1.00:   26.280 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279007
  mean =      3.440 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3285 
    [ 2.500,  5.000) = 268562 
    [ 5.000,  7.500) = 5978 
    [ 7.500, 10.000) = 606 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 125 
    [25.000, 27.500) = 51 

  Percentiles, ms/op:
      p(0.0000) =      1.190 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.186 ms/op
     p(99.0000) =      6.128 ms/op
     p(99.9000) =     20.185 ms/op
     p(99.9900) =     25.333 ms/op
     p(99.9990) =     26.176 ms/op
     p(99.9999) =     26.444 ms/op
    p(100.0000) =     26.444 ms/op


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
# Warmup Iteration   1: 11.935 ±(99.9%) 0.159 ms/op
# Warmup Iteration   2: 4.622 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.154 ±(99.9%) 0.015 ms/op
Iteration   1: 4.110 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.241 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.032 ms/op
                 listUser·p0.99:   7.681 ms/op
                 listUser·p0.999:  21.403 ms/op
                 listUser·p0.9999: 26.189 ms/op
                 listUser·p1.00:   26.739 ms/op

Iteration   2: 4.007 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.769 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   7.832 ms/op
                 listUser·p0.999:  15.008 ms/op
                 listUser·p0.9999: 17.008 ms/op
                 listUser·p1.00:   18.317 ms/op

Iteration   3: 4.004 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.454 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.907 ms/op
                 listUser·p0.99:   7.455 ms/op
                 listUser·p0.999:  15.761 ms/op
                 listUser·p0.9999: 19.726 ms/op
                 listUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237555
  mean =      4.040 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 226531 
    [ 5.000,  7.500) = 8433 
    [ 7.500, 10.000) = 1779 
    [10.000, 12.500) = 313 
    [12.500, 15.000) = 168 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.454 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      4.932 ms/op
     p(99.0000) =      7.660 ms/op
     p(99.9000) =     15.974 ms/op
     p(99.9900) =     24.084 ms/op
     p(99.9990) =     26.649 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.314 ± 6.674  ops/ms
ClientPb.existUser                       thrpt       3   9.779 ± 2.027  ops/ms
ClientPb.getUser                         thrpt       3   9.455 ± 1.875  ops/ms
ClientPb.listUser                        thrpt       3   7.847 ± 2.177  ops/ms
ClientPb.createUser                       avgt       3   3.396 ± 0.765   ms/op
ClientPb.existUser                        avgt       3   3.224 ± 0.358   ms/op
ClientPb.getUser                          avgt       3   3.430 ± 1.365   ms/op
ClientPb.listUser                         avgt       3   3.954 ± 0.509   ms/op
ClientPb.createUser                     sample  275324   3.483 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.417           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.367           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.932           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.276           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.504           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.600           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.178           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.409           ms/op
ClientPb.existUser                      sample  296623   3.232 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.200           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.174           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.486           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.740           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.538           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.960           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.608           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.082           ms/op
ClientPb.getUser                        sample  279007   3.440 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.190           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.293           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.805           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.186           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.128           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.185           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.333           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.444           ms/op
ClientPb.listUser                       sample  237555   4.040 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.454           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.932           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.660           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.974           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.084           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.739           ms/op
