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
# Warmup Iteration   1: 2.461 ops/ms
# Warmup Iteration   2: 6.268 ops/ms
# Warmup Iteration   3: 8.477 ops/ms
Iteration   1: 9.042 ops/ms
Iteration   2: 9.249 ops/ms
Iteration   3: 9.107 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.133 ±(99.9%) 1.929 ops/ms [Average]
  (min, avg, max) = (9.042, 9.133, 9.249), stdev = 0.106
  CI (99.9%): [7.204, 11.062] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.384 ops/ms
# Warmup Iteration   2: 8.860 ops/ms
# Warmup Iteration   3: 9.391 ops/ms
Iteration   1: 9.767 ops/ms
Iteration   2: 10.126 ops/ms
Iteration   3: 9.644 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.846 ±(99.9%) 4.562 ops/ms [Average]
  (min, avg, max) = (9.644, 9.846, 10.126), stdev = 0.250
  CI (99.9%): [5.284, 14.408] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.064 ops/ms
# Warmup Iteration   2: 8.320 ops/ms
# Warmup Iteration   3: 9.067 ops/ms
Iteration   1: 9.251 ops/ms
Iteration   2: 9.591 ops/ms
Iteration   3: 9.249 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.364 ±(99.9%) 3.591 ops/ms [Average]
  (min, avg, max) = (9.249, 9.364, 9.591), stdev = 0.197
  CI (99.9%): [5.773, 12.955] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 2.670 ops/ms
# Warmup Iteration   2: 6.949 ops/ms
# Warmup Iteration   3: 7.609 ops/ms
Iteration   1: 7.885 ops/ms
Iteration   2: 7.736 ops/ms
Iteration   3: 8.060 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.893 ±(99.9%) 2.958 ops/ms [Average]
  (min, avg, max) = (7.736, 7.893, 8.060), stdev = 0.162
  CI (99.9%): [4.935, 10.851] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.100 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.745 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.521 ±(99.9%) 0.009 ms/op
Iteration   1: 3.507 ±(99.9%) 0.004 ms/op
Iteration   2: 3.330 ±(99.9%) 0.010 ms/op
Iteration   3: 3.391 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.410 ±(99.9%) 1.639 ms/op [Average]
  (min, avg, max) = (3.330, 3.410, 3.507), stdev = 0.090
  CI (99.9%): [1.771, 5.048] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.766 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.506 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.282 ±(99.9%) 0.007 ms/op
Iteration   1: 3.276 ±(99.9%) 0.004 ms/op
Iteration   2: 3.349 ±(99.9%) 0.006 ms/op
Iteration   3: 3.209 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.278 ±(99.9%) 1.275 ms/op [Average]
  (min, avg, max) = (3.209, 3.278, 3.349), stdev = 0.070
  CI (99.9%): [2.003, 4.553] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.299 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.760 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.662 ±(99.9%) 0.005 ms/op
Iteration   1: 3.575 ±(99.9%) 0.006 ms/op
Iteration   2: 3.438 ±(99.9%) 0.008 ms/op
Iteration   3: 3.407 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.473 ±(99.9%) 1.628 ms/op [Average]
  (min, avg, max) = (3.407, 3.473, 3.575), stdev = 0.089
  CI (99.9%): [1.845, 5.102] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 11.038 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.607 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.200 ±(99.9%) 0.009 ms/op
Iteration   1: 3.946 ±(99.9%) 0.010 ms/op
Iteration   2: 3.906 ±(99.9%) 0.014 ms/op
Iteration   3: 3.960 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.937 ±(99.9%) 0.516 ms/op [Average]
  (min, avg, max) = (3.906, 3.937, 3.960), stdev = 0.028
  CI (99.9%): [3.422, 4.453] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 10.678 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 3.985 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.787 ±(99.9%) 0.014 ms/op
Iteration   1: 3.521 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.587 ms/op
                 createUser·p0.50:   3.412 ms/op
                 createUser·p0.90:   4.002 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   6.169 ms/op
                 createUser·p0.999:  19.923 ms/op
                 createUser·p0.9999: 25.723 ms/op
                 createUser·p1.00:   27.001 ms/op

Iteration   2: 3.350 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.083 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   5.743 ms/op
                 createUser·p0.999:  21.627 ms/op
                 createUser·p0.9999: 24.165 ms/op
                 createUser·p1.00:   24.412 ms/op

Iteration   3: 3.439 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.599 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   3.969 ms/op
                 createUser·p0.95:   4.465 ms/op
                 createUser·p0.99:   5.522 ms/op
                 createUser·p0.999:  19.999 ms/op
                 createUser·p0.9999: 25.376 ms/op
                 createUser·p1.00:   26.051 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279171
  mean =      3.435 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10404 
    [ 2.500,  5.000) = 263438 
    [ 5.000,  7.500) = 4516 
    [ 7.500, 10.000) = 456 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 116 
    [22.500, 25.000) = 132 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.083 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =     19.923 ms/op
     p(99.9900) =     24.871 ms/op
     p(99.9990) =     26.825 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


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
# Warmup Iteration   1: 9.266 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.766 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.274 ±(99.9%) 0.008 ms/op
Iteration   1: 3.309 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.376 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   4.137 ms/op
                 existUser·p0.99:   5.843 ms/op
                 existUser·p0.999:  13.754 ms/op
                 existUser·p0.9999: 22.118 ms/op
                 existUser·p1.00:   23.101 ms/op

Iteration   2: 3.306 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.114 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   4.055 ms/op
                 existUser·p0.99:   5.308 ms/op
                 existUser·p0.999:  12.419 ms/op
                 existUser·p0.9999: 24.039 ms/op
                 existUser·p1.00:   25.788 ms/op

Iteration   3: 3.216 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.536 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   5.082 ms/op
                 existUser·p0.999:  11.732 ms/op
                 existUser·p0.9999: 25.462 ms/op
                 existUser·p1.00:   26.083 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 293019
  mean =      3.276 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11609 
    [ 2.500,  5.000) = 276100 
    [ 5.000,  7.500) = 4612 
    [ 7.500, 10.000) = 320 
    [10.000, 12.500) = 120 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 133 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.114 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     11.518 ms/op
     p(99.9900) =     24.435 ms/op
     p(99.9990) =     26.020 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


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
# Warmup Iteration   1: 9.064 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.849 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.562 ±(99.9%) 0.011 ms/op
Iteration   1: 3.475 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.540 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   6.570 ms/op
                 getUser·p0.999:  12.321 ms/op
                 getUser·p0.9999: 33.222 ms/op
                 getUser·p1.00:   33.751 ms/op

Iteration   2: 3.516 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.237 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   3.908 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   6.390 ms/op
                 getUser·p0.999:  21.332 ms/op
                 getUser·p0.9999: 28.430 ms/op
                 getUser·p1.00:   29.000 ms/op

Iteration   3: 3.594 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.009 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   3.908 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   7.119 ms/op
                 getUser·p0.999:  19.197 ms/op
                 getUser·p0.9999: 26.745 ms/op
                 getUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271932
  mean =      3.527 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1793 
    [ 2.500,  5.000) = 261911 
    [ 5.000,  7.500) = 6626 
    [ 7.500, 10.000) = 1031 
    [10.000, 12.500) = 260 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.237 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.153 ms/op
     p(99.0000) =      6.660 ms/op
     p(99.9000) =     12.988 ms/op
     p(99.9900) =     32.113 ms/op
     p(99.9990) =     33.573 ms/op
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
# Warmup Iteration   1: 12.119 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 4.702 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.234 ±(99.9%) 0.013 ms/op
Iteration   1: 4.317 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   4.211 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   8.126 ms/op
                 listUser·p0.999:  21.693 ms/op
                 listUser·p0.9999: 24.170 ms/op
                 listUser·p1.00:   24.773 ms/op

Iteration   2: 4.269 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.507 ms/op
                 listUser·p0.50:   4.059 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   8.330 ms/op
                 listUser·p0.999:  16.105 ms/op
                 listUser·p0.9999: 23.527 ms/op
                 listUser·p1.00:   23.593 ms/op

Iteration   3: 4.238 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.433 ms/op
                 listUser·p0.50:   4.125 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.809 ms/op
                 listUser·p0.99:   7.913 ms/op
                 listUser·p0.999:  15.426 ms/op
                 listUser·p0.9999: 22.068 ms/op
                 listUser·p1.00:   24.248 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 224301
  mean =      4.274 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 212974 
    [ 5.000,  7.500) = 8205 
    [ 7.500, 10.000) = 2053 
    [10.000, 12.500) = 528 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 174 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 121 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.286 ms/op
     p(50.0000) =      4.125 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      5.013 ms/op
     p(99.0000) =      8.069 ms/op
     p(99.9000) =     17.138 ms/op
     p(99.9900) =     23.827 ms/op
     p(99.9990) =     24.603 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.133 ± 1.929  ops/ms
ClientPb.existUser                       thrpt       3   9.846 ± 4.562  ops/ms
ClientPb.getUser                         thrpt       3   9.364 ± 3.591  ops/ms
ClientPb.listUser                        thrpt       3   7.893 ± 2.958  ops/ms
ClientPb.createUser                       avgt       3   3.410 ± 1.639   ms/op
ClientPb.existUser                        avgt       3   3.278 ± 1.275   ms/op
ClientPb.getUser                          avgt       3   3.473 ± 1.628   ms/op
ClientPb.listUser                         avgt       3   3.937 ± 0.516   ms/op
ClientPb.createUser                     sample  279171   3.435 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.083           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.346           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.871           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.800           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.923           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.871           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.001           ms/op
ClientPb.existUser                      sample  293019   3.276 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.114           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.191           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.543           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.867           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.595           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.518           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.435           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.083           ms/op
ClientPb.getUser                        sample  271932   3.527 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.237           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.391           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.854           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.153           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.660           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.988           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.113           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.751           ms/op
ClientPb.listUser                       sample  224301   4.274 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.286           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.125           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.628           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.013           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.069           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.138           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.827           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.773           ms/op
