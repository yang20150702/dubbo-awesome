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
# Warmup Iteration   1: 1.967 ops/ms
# Warmup Iteration   2: 5.469 ops/ms
# Warmup Iteration   3: 8.634 ops/ms
Iteration   1: 9.344 ops/ms
Iteration   2: 8.737 ops/ms
Iteration   3: 9.260 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.113 ±(99.9%) 6.003 ops/ms [Average]
  (min, avg, max) = (8.737, 9.113, 9.344), stdev = 0.329
  CI (99.9%): [3.110, 15.117] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.905 ops/ms
# Warmup Iteration   2: 8.544 ops/ms
# Warmup Iteration   3: 9.332 ops/ms
Iteration   1: 10.092 ops/ms
Iteration   2: 9.975 ops/ms
Iteration   3: 9.825 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.964 ±(99.9%) 2.440 ops/ms [Average]
  (min, avg, max) = (9.825, 9.964, 10.092), stdev = 0.134
  CI (99.9%): [7.524, 12.404] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.023 ops/ms
# Warmup Iteration   2: 8.633 ops/ms
# Warmup Iteration   3: 9.064 ops/ms
Iteration   1: 9.323 ops/ms
Iteration   2: 9.403 ops/ms
Iteration   3: 9.351 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.359 ±(99.9%) 0.733 ops/ms [Average]
  (min, avg, max) = (9.323, 9.359, 9.403), stdev = 0.040
  CI (99.9%): [8.626, 10.092] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 2.748 ops/ms
# Warmup Iteration   2: 7.182 ops/ms
# Warmup Iteration   3: 7.580 ops/ms
Iteration   1: 7.865 ops/ms
Iteration   2: 8.212 ops/ms
Iteration   3: 7.888 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.988 ±(99.9%) 3.545 ops/ms [Average]
  (min, avg, max) = (7.865, 7.988, 8.212), stdev = 0.194
  CI (99.9%): [4.443, 11.533] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 10.989 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.783 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.626 ±(99.9%) 0.006 ms/op
Iteration   1: 3.506 ±(99.9%) 0.004 ms/op
Iteration   2: 3.371 ±(99.9%) 0.007 ms/op
Iteration   3: 3.331 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.403 ±(99.9%) 1.670 ms/op [Average]
  (min, avg, max) = (3.331, 3.403, 3.506), stdev = 0.092
  CI (99.9%): [1.733, 5.072] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.801 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.022 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.465 ±(99.9%) 0.007 ms/op
Iteration   1: 3.249 ±(99.9%) 0.012 ms/op
Iteration   2: 3.195 ±(99.9%) 0.011 ms/op
Iteration   3: 3.239 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.228 ±(99.9%) 0.521 ms/op [Average]
  (min, avg, max) = (3.195, 3.228, 3.249), stdev = 0.029
  CI (99.9%): [2.707, 3.748] (assumes normal distribution)


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
# Warmup Iteration   1: 9.405 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.648 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.611 ±(99.9%) 0.004 ms/op
Iteration   1: 3.352 ±(99.9%) 0.007 ms/op
Iteration   2: 3.357 ±(99.9%) 0.009 ms/op
Iteration   3: 3.426 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.379 ±(99.9%) 0.757 ms/op [Average]
  (min, avg, max) = (3.352, 3.379, 3.426), stdev = 0.041
  CI (99.9%): [2.622, 4.135] (assumes normal distribution)


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
# Warmup Iteration   1: 11.625 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.446 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.007 ±(99.9%) 0.010 ms/op
Iteration   1: 3.926 ±(99.9%) 0.009 ms/op
Iteration   2: 3.976 ±(99.9%) 0.008 ms/op
Iteration   3: 4.001 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.967 ±(99.9%) 0.700 ms/op [Average]
  (min, avg, max) = (3.926, 3.967, 4.001), stdev = 0.038
  CI (99.9%): [3.268, 4.667] (assumes normal distribution)


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
# Warmup Iteration   1: 10.411 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.927 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.732 ±(99.9%) 0.014 ms/op
Iteration   1: 3.361 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.501 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   4.047 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  20.205 ms/op
                 createUser·p0.9999: 23.494 ms/op
                 createUser·p1.00:   24.347 ms/op

Iteration   2: 3.365 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.458 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   5.349 ms/op
                 createUser·p0.999:  22.013 ms/op
                 createUser·p0.9999: 26.034 ms/op
                 createUser·p1.00:   27.492 ms/op

Iteration   3: 3.410 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.137 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   4.112 ms/op
                 createUser·p0.99:   5.463 ms/op
                 createUser·p0.999:  20.129 ms/op
                 createUser·p0.9999: 27.620 ms/op
                 createUser·p1.00:   29.983 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283965
  mean =      3.379 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9870 
    [ 2.500,  5.000) = 269504 
    [ 5.000,  7.500) = 3477 
    [ 7.500, 10.000) = 662 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 123 
    [25.000, 27.500) = 59 

  Percentiles, ms/op:
      p(0.0000) =      1.137 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     20.152 ms/op
     p(99.9900) =     26.615 ms/op
     p(99.9990) =     29.009 ms/op
     p(99.9999) =     29.983 ms/op
    p(100.0000) =     29.983 ms/op


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
# Warmup Iteration   1: 10.480 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.651 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.477 ±(99.9%) 0.011 ms/op
Iteration   1: 3.562 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.343 ms/op
                 existUser·p0.50:   3.371 ms/op
                 existUser·p0.90:   4.342 ms/op
                 existUser·p0.95:   4.981 ms/op
                 existUser·p0.99:   6.636 ms/op
                 existUser·p0.999:  20.724 ms/op
                 existUser·p0.9999: 22.839 ms/op
                 existUser·p1.00:   23.757 ms/op

Iteration   2: 3.422 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.110 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   4.276 ms/op
                 existUser·p0.95:   4.506 ms/op
                 existUser·p0.99:   5.677 ms/op
                 existUser·p0.999:  14.976 ms/op
                 existUser·p0.9999: 23.888 ms/op
                 existUser·p1.00:   24.805 ms/op

Iteration   3: 3.342 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.638 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   4.120 ms/op
                 existUser·p0.99:   5.988 ms/op
                 existUser·p0.999:  20.476 ms/op
                 existUser·p0.9999: 41.710 ms/op
                 existUser·p1.00:   42.861 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 278792
  mean =      3.439 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 270154 
    [ 5.000, 10.000) = 8262 
    [10.000, 15.000) = 92 
    [15.000, 20.000) = 22 
    [20.000, 25.000) = 198 
    [25.000, 30.000) = 32 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 5 
    [40.000, 45.000) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.343 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      6.160 ms/op
     p(99.9000) =     15.211 ms/op
     p(99.9900) =     40.001 ms/op
     p(99.9990) =     42.088 ms/op
     p(99.9999) =     42.861 ms/op
    p(100.0000) =     42.861 ms/op


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
# Warmup Iteration   1: 10.181 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 3.840 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.484 ±(99.9%) 0.010 ms/op
Iteration   1: 3.547 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.235 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   5.063 ms/op
                 getUser·p0.99:   7.586 ms/op
                 getUser·p0.999:  18.811 ms/op
                 getUser·p0.9999: 21.889 ms/op
                 getUser·p1.00:   22.839 ms/op

Iteration   2: 3.387 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.278 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   5.956 ms/op
                 getUser·p0.999:  21.913 ms/op
                 getUser·p0.9999: 28.151 ms/op
                 getUser·p1.00:   29.917 ms/op

Iteration   3: 3.313 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.223 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   5.620 ms/op
                 getUser·p0.999:  14.699 ms/op
                 getUser·p0.9999: 27.354 ms/op
                 getUser·p1.00:   29.360 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 281113
  mean =      3.413 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3616 
    [ 2.500,  5.000) = 268277 
    [ 5.000,  7.500) = 7569 
    [ 7.500, 10.000) = 1102 
    [10.000, 12.500) = 180 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 61 

  Percentiles, ms/op:
      p(0.0000) =      1.223 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      6.750 ms/op
     p(99.9000) =     18.900 ms/op
     p(99.9900) =     27.259 ms/op
     p(99.9990) =     29.121 ms/op
     p(99.9999) =     29.917 ms/op
    p(100.0000) =     29.917 ms/op


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
# Warmup Iteration   1: 11.825 ±(99.9%) 0.169 ms/op
# Warmup Iteration   2: 4.380 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.084 ±(99.9%) 0.013 ms/op
Iteration   1: 3.998 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.720 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  19.660 ms/op
                 listUser·p0.9999: 29.223 ms/op
                 listUser·p1.00:   33.489 ms/op

Iteration   2: 3.891 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.083 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   7.340 ms/op
                 listUser·p0.999:  15.956 ms/op
                 listUser·p0.9999: 19.530 ms/op
                 listUser·p1.00:   19.923 ms/op

Iteration   3: 3.942 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.363 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  14.893 ms/op
                 listUser·p0.9999: 16.679 ms/op
                 listUser·p1.00:   16.941 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 243280
  mean =      3.943 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42 
    [ 2.500,  5.000) = 235898 
    [ 5.000,  7.500) = 5412 
    [ 7.500, 10.000) = 1168 
    [10.000, 12.500) = 260 
    [12.500, 15.000) = 157 
    [15.000, 17.500) = 169 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.720 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     16.019 ms/op
     p(99.9900) =     21.780 ms/op
     p(99.9990) =     31.063 ms/op
     p(99.9999) =     33.489 ms/op
    p(100.0000) =     33.489 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.113 ± 6.003  ops/ms
ClientPb.existUser                       thrpt       3   9.964 ± 2.440  ops/ms
ClientPb.getUser                         thrpt       3   9.359 ± 0.733  ops/ms
ClientPb.listUser                        thrpt       3   7.988 ± 3.545  ops/ms
ClientPb.createUser                       avgt       3   3.403 ± 1.670   ms/op
ClientPb.existUser                        avgt       3   3.228 ± 0.521   ms/op
ClientPb.getUser                          avgt       3   3.379 ± 0.757   ms/op
ClientPb.listUser                         avgt       3   3.967 ± 0.700   ms/op
ClientPb.createUser                     sample  283965   3.379 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.137           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.305           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.781           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.080           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.603           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.152           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.615           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.983           ms/op
ClientPb.existUser                      sample  278792   3.439 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.343           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.281           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.100           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.571           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.160           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.211           ms/op
ClientPb.existUser:existUser·p0.9999    sample          40.001           ms/op
ClientPb.existUser:existUser·p1.00      sample          42.861           ms/op
ClientPb.getUser                        sample  281113   3.413 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.223           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.260           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.756           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.133           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.750           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.900           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.259           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.917           ms/op
ClientPb.listUser                       sample  243280   3.943 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.720           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.805           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.070           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.019           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.780           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.489           ms/op
