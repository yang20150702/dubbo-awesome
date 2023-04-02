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
# Warmup Iteration   1: 1.987 ops/ms
# Warmup Iteration   2: 5.473 ops/ms
# Warmup Iteration   3: 8.691 ops/ms
Iteration   1: 9.488 ops/ms
Iteration   2: 9.112 ops/ms
Iteration   3: 9.622 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.407 ±(99.9%) 4.824 ops/ms [Average]
  (min, avg, max) = (9.112, 9.407, 9.622), stdev = 0.264
  CI (99.9%): [4.583, 14.231] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.010 ops/ms
# Warmup Iteration   2: 8.278 ops/ms
# Warmup Iteration   3: 9.361 ops/ms
Iteration   1: 9.390 ops/ms
Iteration   2: 9.765 ops/ms
Iteration   3: 9.652 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.602 ±(99.9%) 3.516 ops/ms [Average]
  (min, avg, max) = (9.390, 9.602, 9.765), stdev = 0.193
  CI (99.9%): [6.087, 13.118] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.779 ops/ms
# Warmup Iteration   2: 8.215 ops/ms
# Warmup Iteration   3: 9.330 ops/ms
Iteration   1: 9.404 ops/ms
Iteration   2: 9.458 ops/ms
Iteration   3: 9.131 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.331 ±(99.9%) 3.197 ops/ms [Average]
  (min, avg, max) = (9.131, 9.331, 9.458), stdev = 0.175
  CI (99.9%): [6.134, 12.528] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.575 ops/ms
# Warmup Iteration   2: 7.104 ops/ms
# Warmup Iteration   3: 7.699 ops/ms
Iteration   1: 8.292 ops/ms
Iteration   2: 8.007 ops/ms
Iteration   3: 8.259 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.186 ±(99.9%) 2.847 ops/ms [Average]
  (min, avg, max) = (8.007, 8.186, 8.292), stdev = 0.156
  CI (99.9%): [5.339, 11.033] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.347 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.893 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.473 ±(99.9%) 0.008 ms/op
Iteration   1: 3.464 ±(99.9%) 0.005 ms/op
Iteration   2: 3.462 ±(99.9%) 0.004 ms/op
Iteration   3: 3.404 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.443 ±(99.9%) 0.622 ms/op [Average]
  (min, avg, max) = (3.404, 3.443, 3.464), stdev = 0.034
  CI (99.9%): [2.821, 4.066] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 9.342 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.575 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.466 ±(99.9%) 0.006 ms/op
Iteration   1: 3.245 ±(99.9%) 0.004 ms/op
Iteration   2: 3.284 ±(99.9%) 0.004 ms/op
Iteration   3: 3.225 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.251 ±(99.9%) 0.552 ms/op [Average]
  (min, avg, max) = (3.225, 3.251, 3.284), stdev = 0.030
  CI (99.9%): [2.700, 3.803] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.275 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.771 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.580 ±(99.9%) 0.005 ms/op
Iteration   1: 3.600 ±(99.9%) 0.007 ms/op
Iteration   2: 3.489 ±(99.9%) 0.006 ms/op
Iteration   3: 3.320 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.469 ±(99.9%) 2.573 ms/op [Average]
  (min, avg, max) = (3.320, 3.469, 3.600), stdev = 0.141
  CI (99.9%): [0.897, 6.042] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.350 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.365 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.099 ±(99.9%) 0.005 ms/op
Iteration   1: 3.981 ±(99.9%) 0.012 ms/op
Iteration   2: 3.907 ±(99.9%) 0.013 ms/op
Iteration   3: 3.988 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.959 ±(99.9%) 0.820 ms/op [Average]
  (min, avg, max) = (3.907, 3.959, 3.988), stdev = 0.045
  CI (99.9%): [3.139, 4.779] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 11.116 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.060 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.769 ±(99.9%) 0.014 ms/op
Iteration   1: 3.444 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.522 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   6.259 ms/op
                 createUser·p0.999:  20.052 ms/op
                 createUser·p0.9999: 23.190 ms/op
                 createUser·p1.00:   23.757 ms/op

Iteration   2: 3.397 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.182 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.809 ms/op
                 createUser·p0.95:   4.145 ms/op
                 createUser·p0.99:   5.939 ms/op
                 createUser·p0.999:  21.193 ms/op
                 createUser·p0.9999: 31.429 ms/op
                 createUser·p1.00:   32.571 ms/op

Iteration   3: 3.495 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.761 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   4.202 ms/op
                 createUser·p0.95:   4.506 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  20.727 ms/op
                 createUser·p0.9999: 26.111 ms/op
                 createUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278777
  mean =      3.445 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13083 
    [ 2.500,  5.000) = 259070 
    [ 5.000,  7.500) = 5403 
    [ 7.500, 10.000) = 729 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 131 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.182 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =     20.225 ms/op
     p(99.9900) =     29.692 ms/op
     p(99.9990) =     32.513 ms/op
     p(99.9999) =     32.571 ms/op
    p(100.0000) =     32.571 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.495 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.637 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.475 ±(99.9%) 0.009 ms/op
Iteration   1: 3.398 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.524 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.842 ms/op
                 existUser·p0.95:   4.145 ms/op
                 existUser·p0.99:   5.947 ms/op
                 existUser·p0.999:  20.405 ms/op
                 existUser·p0.9999: 23.284 ms/op
                 existUser·p1.00:   24.543 ms/op

Iteration   2: 3.413 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.143 ms/op
                 existUser·p0.50:   3.375 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   4.116 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  21.807 ms/op
                 existUser·p0.9999: 23.661 ms/op
                 existUser·p1.00:   24.609 ms/op

Iteration   3: 3.372 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.561 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.916 ms/op
                 existUser·p0.95:   4.186 ms/op
                 existUser·p0.99:   5.759 ms/op
                 existUser·p0.999:  9.093 ms/op
                 existUser·p0.9999: 27.903 ms/op
                 existUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282789
  mean =      3.394 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11512 
    [ 2.500,  5.000) = 265583 
    [ 5.000,  7.500) = 5042 
    [ 7.500, 10.000) = 373 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 113 
    [25.000, 27.500) = 43 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.157 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =      9.621 ms/op
     p(99.9900) =     26.917 ms/op
     p(99.9990) =     28.475 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.878 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 3.872 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.525 ±(99.9%) 0.010 ms/op
Iteration   1: 3.579 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.651 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   4.284 ms/op
                 getUser·p0.95:   5.104 ms/op
                 getUser·p0.99:   7.037 ms/op
                 getUser·p0.999:  11.788 ms/op
                 getUser·p0.9999: 21.727 ms/op
                 getUser·p1.00:   22.479 ms/op

Iteration   2: 3.386 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.294 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   4.043 ms/op
                 getUser·p0.99:   5.784 ms/op
                 getUser·p0.999:  22.330 ms/op
                 getUser·p0.9999: 25.270 ms/op
                 getUser·p1.00:   26.051 ms/op

Iteration   3: 3.427 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.348 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   6.463 ms/op
                 getUser·p0.999:  18.890 ms/op
                 getUser·p0.9999: 26.536 ms/op
                 getUser·p1.00:   27.984 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277070
  mean =      3.462 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8978 
    [ 2.500,  5.000) = 258105 
    [ 5.000,  7.500) = 8688 
    [ 7.500, 10.000) = 870 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 124 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      1.294 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      6.439 ms/op
     p(99.9000) =     11.911 ms/op
     p(99.9900) =     25.494 ms/op
     p(99.9990) =     27.402 ms/op
     p(99.9999) =     27.984 ms/op
    p(100.0000) =     27.984 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.712 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.509 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.170 ±(99.9%) 0.014 ms/op
Iteration   1: 4.041 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.195 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   7.602 ms/op
                 listUser·p0.999:  21.529 ms/op
                 listUser·p0.9999: 25.300 ms/op
                 listUser·p1.00:   25.723 ms/op

Iteration   2: 3.968 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.733 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   7.750 ms/op
                 listUser·p0.999:  16.695 ms/op
                 listUser·p0.9999: 19.102 ms/op
                 listUser·p1.00:   19.628 ms/op

Iteration   3: 3.921 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.052 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  19.137 ms/op
                 listUser·p0.9999: 23.713 ms/op
                 listUser·p1.00:   25.231 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241209
  mean =      3.976 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25 
    [ 2.500,  5.000) = 233526 
    [ 5.000,  7.500) = 5253 
    [ 7.500, 10.000) = 1408 
    [10.000, 12.500) = 421 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 202 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.733 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      7.495 ms/op
     p(99.9000) =     18.383 ms/op
     p(99.9900) =     23.953 ms/op
     p(99.9990) =     25.650 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.407 ± 4.824  ops/ms
ClientPb.existUser                       thrpt       3   9.602 ± 3.516  ops/ms
ClientPb.getUser                         thrpt       3   9.331 ± 3.197  ops/ms
ClientPb.listUser                        thrpt       3   8.186 ± 2.847  ops/ms
ClientPb.createUser                       avgt       3   3.443 ± 0.622   ms/op
ClientPb.existUser                        avgt       3   3.251 ± 0.552   ms/op
ClientPb.getUser                          avgt       3   3.469 ± 2.573   ms/op
ClientPb.listUser                         avgt       3   3.959 ± 0.820   ms/op
ClientPb.createUser                     sample  278777   3.445 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.182           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.342           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.949           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.366           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.964           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.225           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.692           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.571           ms/op
ClientPb.existUser                      sample  282789   3.394 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.143           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.326           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.838           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.157           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.784           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.621           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.917           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.574           ms/op
ClientPb.getUser                        sample  277070   3.462 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.294           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.301           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.973           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.448           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.439           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.911           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.494           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.984           ms/op
ClientPb.listUser                       sample  241209   3.976 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.733           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.813           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.645           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.495           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.383           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.953           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.723           ms/op
