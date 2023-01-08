# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.537 ops/ms
# Warmup Iteration   2: 6.432 ops/ms
# Warmup Iteration   3: 9.028 ops/ms
Iteration   1: 10.077 ops/ms
Iteration   2: 9.944 ops/ms
Iteration   3: 9.980 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.000 ±(99.9%) 1.253 ops/ms [Average]
  (min, avg, max) = (9.944, 10.000, 10.077), stdev = 0.069
  CI (99.9%): [8.748, 11.253] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.687 ops/ms
# Warmup Iteration   2: 9.506 ops/ms
# Warmup Iteration   3: 10.479 ops/ms
Iteration   1: 10.270 ops/ms
Iteration   2: 10.659 ops/ms
Iteration   3: 10.814 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.581 ±(99.9%) 5.106 ops/ms [Average]
  (min, avg, max) = (10.270, 10.581, 10.814), stdev = 0.280
  CI (99.9%): [5.475, 15.688] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.456 ops/ms
# Warmup Iteration   2: 9.462 ops/ms
# Warmup Iteration   3: 9.663 ops/ms
Iteration   1: 10.229 ops/ms
Iteration   2: 9.953 ops/ms
Iteration   3: 10.070 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.084 ±(99.9%) 2.526 ops/ms [Average]
  (min, avg, max) = (9.953, 10.084, 10.229), stdev = 0.138
  CI (99.9%): [7.558, 12.609] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.405 ops/ms
# Warmup Iteration   2: 7.224 ops/ms
# Warmup Iteration   3: 8.430 ops/ms
Iteration   1: 8.615 ops/ms
Iteration   2: 8.737 ops/ms
Iteration   3: 8.768 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.707 ±(99.9%) 1.479 ops/ms [Average]
  (min, avg, max) = (8.615, 8.707, 8.768), stdev = 0.081
  CI (99.9%): [7.228, 10.186] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.905 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.554 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.320 ±(99.9%) 0.005 ms/op
Iteration   1: 3.288 ±(99.9%) 0.006 ms/op
Iteration   2: 3.227 ±(99.9%) 0.007 ms/op
Iteration   3: 3.153 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.223 ±(99.9%) 1.233 ms/op [Average]
  (min, avg, max) = (3.153, 3.223, 3.288), stdev = 0.068
  CI (99.9%): [1.989, 4.456] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.809 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.294 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.195 ±(99.9%) 0.004 ms/op
Iteration   1: 3.051 ±(99.9%) 0.002 ms/op
Iteration   2: 3.027 ±(99.9%) 0.006 ms/op
Iteration   3: 2.942 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.007 ±(99.9%) 1.047 ms/op [Average]
  (min, avg, max) = (2.942, 3.007, 3.051), stdev = 0.057
  CI (99.9%): [1.960, 4.054] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.026 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.385 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.384 ±(99.9%) 0.005 ms/op
Iteration   1: 3.307 ±(99.9%) 0.003 ms/op
Iteration   2: 3.138 ±(99.9%) 0.004 ms/op
Iteration   3: 3.260 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.235 ±(99.9%) 1.586 ms/op [Average]
  (min, avg, max) = (3.138, 3.235, 3.307), stdev = 0.087
  CI (99.9%): [1.649, 4.821] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.266 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.192 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.741 ±(99.9%) 0.006 ms/op
Iteration   1: 3.662 ±(99.9%) 0.006 ms/op
Iteration   2: 3.720 ±(99.9%) 0.007 ms/op
Iteration   3: 3.624 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.669 ±(99.9%) 0.877 ms/op [Average]
  (min, avg, max) = (3.624, 3.669, 3.720), stdev = 0.048
  CI (99.9%): [2.792, 4.546] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.216 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.801 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.331 ±(99.9%) 0.009 ms/op
Iteration   1: 3.330 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.702 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   5.743 ms/op
                 createUser·p0.999:  17.121 ms/op
                 createUser·p0.9999: 20.951 ms/op
                 createUser·p1.00:   21.627 ms/op

Iteration   2: 3.141 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.174 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   5.382 ms/op
                 createUser·p0.999:  17.830 ms/op
                 createUser·p0.9999: 22.669 ms/op
                 createUser·p1.00:   22.938 ms/op

Iteration   3: 3.136 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.509 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.355 ms/op
                 createUser·p0.95:   3.641 ms/op
                 createUser·p0.99:   5.259 ms/op
                 createUser·p0.999:  14.826 ms/op
                 createUser·p0.9999: 20.801 ms/op
                 createUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 299946
  mean =      3.200 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20621 
    [ 2.500,  5.000) = 273433 
    [ 5.000,  7.500) = 5037 
    [ 7.500, 10.000) = 369 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 122 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.702 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =     15.795 ms/op
     p(99.9900) =     22.315 ms/op
     p(99.9990) =     22.774 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.272 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.406 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.200 ±(99.9%) 0.009 ms/op
Iteration   1: 3.066 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.673 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.236 ms/op
                 existUser·p0.95:   3.482 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  9.830 ms/op
                 existUser·p0.9999: 26.626 ms/op
                 existUser·p1.00:   27.165 ms/op

Iteration   2: 3.124 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.214 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  9.840 ms/op
                 existUser·p0.9999: 25.773 ms/op
                 existUser·p1.00:   26.182 ms/op

Iteration   3: 3.072 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.122 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.506 ms/op
                 existUser·p0.99:   5.210 ms/op
                 existUser·p0.999:  10.322 ms/op
                 existUser·p0.9999: 21.427 ms/op
                 existUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 310928
  mean =      3.087 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20464 
    [ 2.500,  5.000) = 286055 
    [ 5.000,  7.500) = 3679 
    [ 7.500, 10.000) = 425 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 59 

  Percentiles, ms/op:
      p(0.0000) =      0.673 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.351 ms/op
     p(95.0000) =      3.650 ms/op
     p(99.0000) =      5.300 ms/op
     p(99.9000) =      9.848 ms/op
     p(99.9900) =     26.051 ms/op
     p(99.9990) =     27.026 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.020 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.444 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.290 ±(99.9%) 0.009 ms/op
Iteration   1: 3.138 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.002 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.404 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   5.480 ms/op
                 getUser·p0.999:  18.940 ms/op
                 getUser·p0.9999: 23.757 ms/op
                 getUser·p1.00:   24.412 ms/op

Iteration   2: 3.177 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.869 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   5.300 ms/op
                 getUser·p0.999:  11.818 ms/op
                 getUser·p0.9999: 25.705 ms/op
                 getUser·p1.00:   26.739 ms/op

Iteration   3: 3.300 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.327 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.908 ms/op
                 getUser·p0.95:   4.727 ms/op
                 getUser·p0.99:   6.185 ms/op
                 getUser·p0.999:  12.614 ms/op
                 getUser·p0.9999: 22.073 ms/op
                 getUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299598
  mean =      3.203 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12571 
    [ 2.500,  5.000) = 279808 
    [ 5.000,  7.500) = 6461 
    [ 7.500, 10.000) = 359 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 141 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.869 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      4.186 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =     17.426 ms/op
     p(99.9900) =     24.218 ms/op
     p(99.9990) =     26.673 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.354 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 4.125 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.843 ±(99.9%) 0.012 ms/op
Iteration   1: 3.796 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.157 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  15.385 ms/op
                 listUser·p0.9999: 21.154 ms/op
                 listUser·p1.00:   22.512 ms/op

Iteration   2: 3.759 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.749 ms/op
                 listUser·p0.50:   3.637 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   7.033 ms/op
                 listUser·p0.999:  15.316 ms/op
                 listUser·p0.9999: 17.678 ms/op
                 listUser·p1.00:   18.645 ms/op

Iteration   3: 3.686 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.228 ms/op
                 listUser·p0.50:   3.518 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   7.338 ms/op
                 listUser·p0.999:  13.128 ms/op
                 listUser·p0.9999: 15.870 ms/op
                 listUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256032
  mean =      3.746 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 68 
    [ 2.500,  5.000) = 246930 
    [ 5.000,  7.500) = 7375 
    [ 7.500, 10.000) = 937 
    [10.000, 12.500) = 307 
    [12.500, 15.000) = 191 
    [15.000, 17.500) = 172 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.157 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     14.647 ms/op
     p(99.9900) =     19.634 ms/op
     p(99.9990) =     22.346 ms/op
     p(99.9999) =     22.512 ms/op
    p(100.0000) =     22.512 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.000 ± 1.253  ops/ms
ClientPb.existUser                       thrpt       3  10.581 ± 5.106  ops/ms
ClientPb.getUser                         thrpt       3  10.084 ± 2.526  ops/ms
ClientPb.listUser                        thrpt       3   8.707 ± 1.479  ops/ms
ClientPb.createUser                       avgt       3   3.223 ± 1.233   ms/op
ClientPb.existUser                        avgt       3   3.007 ± 1.047   ms/op
ClientPb.getUser                          avgt       3   3.235 ± 1.586   ms/op
ClientPb.listUser                         avgt       3   3.669 ± 0.877   ms/op
ClientPb.createUser                     sample  299946   3.200 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.702           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.588           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.961           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.415           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.795           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.315           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.938           ms/op
ClientPb.existUser                      sample  310928   3.087 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.673           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.351           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.650           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.300           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.848           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.051           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.165           ms/op
ClientPb.getUser                        sample  299598   3.203 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.869           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.580           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.186           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.652           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.426           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.218           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.739           ms/op
ClientPb.listUser                       sample  256032   3.746 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.157           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.633           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.190           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.086           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.647           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.634           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.512           ms/op
