# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.131 ops/ms
# Warmup Iteration   2: 5.567 ops/ms
# Warmup Iteration   3: 8.546 ops/ms
Iteration   1: 9.330 ops/ms
Iteration   2: 9.239 ops/ms
Iteration   3: 9.493 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.354 ±(99.9%) 2.349 ops/ms [Average]
  (min, avg, max) = (9.239, 9.354, 9.493), stdev = 0.129
  CI (99.9%): [7.006, 11.703] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.164 ops/ms
# Warmup Iteration   2: 8.834 ops/ms
# Warmup Iteration   3: 9.455 ops/ms
Iteration   1: 9.487 ops/ms
Iteration   2: 9.448 ops/ms
Iteration   3: 9.548 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.494 ±(99.9%) 0.917 ops/ms [Average]
  (min, avg, max) = (9.448, 9.494, 9.548), stdev = 0.050
  CI (99.9%): [8.578, 10.411] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.285 ops/ms
# Warmup Iteration   2: 8.911 ops/ms
# Warmup Iteration   3: 9.232 ops/ms
Iteration   1: 8.824 ops/ms
Iteration   2: 9.402 ops/ms
Iteration   3: 9.339 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.188 ±(99.9%) 5.784 ops/ms [Average]
  (min, avg, max) = (8.824, 9.188, 9.402), stdev = 0.317
  CI (99.9%): [3.404, 14.973] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.166 ops/ms
# Warmup Iteration   2: 7.240 ops/ms
# Warmup Iteration   3: 7.863 ops/ms
Iteration   1: 8.199 ops/ms
Iteration   2: 7.861 ops/ms
Iteration   3: 8.079 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.047 ±(99.9%) 3.121 ops/ms [Average]
  (min, avg, max) = (7.861, 8.047, 8.199), stdev = 0.171
  CI (99.9%): [4.925, 11.168] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.237 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.770 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.490 ±(99.9%) 0.005 ms/op
Iteration   1: 3.385 ±(99.9%) 0.009 ms/op
Iteration   2: 3.504 ±(99.9%) 0.008 ms/op
Iteration   3: 3.423 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.437 ±(99.9%) 1.109 ms/op [Average]
  (min, avg, max) = (3.385, 3.437, 3.504), stdev = 0.061
  CI (99.9%): [2.329, 4.546] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.526 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.836 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.318 ±(99.9%) 0.005 ms/op
Iteration   1: 3.355 ±(99.9%) 0.004 ms/op
Iteration   2: 3.291 ±(99.9%) 0.010 ms/op
Iteration   3: 3.373 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.340 ±(99.9%) 0.787 ms/op [Average]
  (min, avg, max) = (3.291, 3.340, 3.373), stdev = 0.043
  CI (99.9%): [2.553, 4.127] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.712 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.588 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.593 ±(99.9%) 0.003 ms/op
Iteration   1: 3.404 ±(99.9%) 0.004 ms/op
Iteration   2: 3.364 ±(99.9%) 0.009 ms/op
Iteration   3: 3.304 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.358 ±(99.9%) 0.916 ms/op [Average]
  (min, avg, max) = (3.304, 3.358, 3.404), stdev = 0.050
  CI (99.9%): [2.441, 4.274] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.654 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.556 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.093 ±(99.9%) 0.009 ms/op
Iteration   1: 3.969 ±(99.9%) 0.011 ms/op
Iteration   2: 3.978 ±(99.9%) 0.009 ms/op
Iteration   3: 3.887 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.945 ±(99.9%) 0.913 ms/op [Average]
  (min, avg, max) = (3.887, 3.945, 3.978), stdev = 0.050
  CI (99.9%): [3.032, 4.858] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.992 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 3.971 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.430 ±(99.9%) 0.010 ms/op
Iteration   1: 3.424 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.421 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   5.538 ms/op
                 createUser·p0.999:  20.496 ms/op
                 createUser·p0.9999: 30.278 ms/op
                 createUser·p1.00:   31.031 ms/op

Iteration   2: 3.426 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.914 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   6.079 ms/op
                 createUser·p0.999:  22.211 ms/op
                 createUser·p0.9999: 28.693 ms/op
                 createUser·p1.00:   29.360 ms/op

Iteration   3: 3.416 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.253 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   3.809 ms/op
                 createUser·p0.95:   4.116 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  16.908 ms/op
                 createUser·p0.9999: 23.909 ms/op
                 createUser·p1.00:   24.445 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280327
  mean =      3.422 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18165 
    [ 2.500,  5.000) = 255703 
    [ 5.000,  7.500) = 5669 
    [ 7.500, 10.000) = 414 
    [10.000, 12.500) = 19 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.421 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =     17.105 ms/op
     p(99.9900) =     28.836 ms/op
     p(99.9990) =     30.801 ms/op
     p(99.9999) =     31.031 ms/op
    p(100.0000) =     31.031 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.059 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.543 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.459 ±(99.9%) 0.009 ms/op
Iteration   1: 3.303 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.417 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   4.100 ms/op
                 existUser·p0.99:   5.800 ms/op
                 existUser·p0.999:  11.370 ms/op
                 existUser·p0.9999: 24.095 ms/op
                 existUser·p1.00:   25.002 ms/op

Iteration   2: 3.251 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.448 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   5.890 ms/op
                 existUser·p0.999:  13.775 ms/op
                 existUser·p0.9999: 24.391 ms/op
                 existUser·p1.00:   25.854 ms/op

Iteration   3: 3.322 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.470 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   4.153 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  17.179 ms/op
                 existUser·p0.9999: 25.473 ms/op
                 existUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 291266
  mean =      3.292 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9458 
    [ 2.500,  5.000) = 276252 
    [ 5.000,  7.500) = 4589 
    [ 7.500, 10.000) = 567 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.417 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     12.226 ms/op
     p(99.9900) =     24.543 ms/op
     p(99.9990) =     26.655 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 9.301 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.741 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.480 ±(99.9%) 0.010 ms/op
Iteration   1: 3.453 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.298 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   4.141 ms/op
                 getUser·p0.99:   6.698 ms/op
                 getUser·p0.999:  19.532 ms/op
                 getUser·p0.9999: 22.020 ms/op
                 getUser·p1.00:   22.512 ms/op

Iteration   2: 3.356 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.929 ms/op
                 getUser·p0.50:   3.232 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   5.423 ms/op
                 getUser·p0.999:  21.745 ms/op
                 getUser·p0.9999: 24.934 ms/op
                 getUser·p1.00:   25.919 ms/op

Iteration   3: 3.497 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.585 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   4.153 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   6.144 ms/op
                 getUser·p0.999:  9.215 ms/op
                 getUser·p0.9999: 27.848 ms/op
                 getUser·p1.00:   28.738 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279576
  mean =      3.434 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9328 
    [ 2.500,  5.000) = 263272 
    [ 5.000,  7.500) = 5951 
    [ 7.500, 10.000) = 703 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 116 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 43 

  Percentiles, ms/op:
      p(0.0000) =      0.929 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.095 ms/op
     p(99.9000) =     13.193 ms/op
     p(99.9900) =     26.281 ms/op
     p(99.9990) =     28.104 ms/op
     p(99.9999) =     28.738 ms/op
    p(100.0000) =     28.738 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.270 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.596 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.164 ±(99.9%) 0.014 ms/op
Iteration   1: 4.036 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.440 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   7.274 ms/op
                 listUser·p0.999:  20.536 ms/op
                 listUser·p0.9999: 23.694 ms/op
                 listUser·p1.00:   24.904 ms/op

Iteration   2: 4.036 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.515 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   7.438 ms/op
                 listUser·p0.999:  15.712 ms/op
                 listUser·p0.9999: 16.817 ms/op
                 listUser·p1.00:   18.121 ms/op

Iteration   3: 4.115 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.884 ms/op
                 listUser·p0.50:   3.981 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   7.946 ms/op
                 listUser·p0.999:  14.470 ms/op
                 listUser·p0.9999: 17.826 ms/op
                 listUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236200
  mean =      4.062 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43 
    [ 2.500,  5.000) = 227548 
    [ 5.000,  7.500) = 6066 
    [ 7.500, 10.000) = 1796 
    [10.000, 12.500) = 263 
    [12.500, 15.000) = 199 
    [15.000, 17.500) = 175 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.440 ms/op
     p(50.0000) =      3.924 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      7.676 ms/op
     p(99.9000) =     15.778 ms/op
     p(99.9900) =     22.688 ms/op
     p(99.9990) =     24.189 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.354 ± 2.349  ops/ms
ClientPb.existUser                       thrpt       3   9.494 ± 0.917  ops/ms
ClientPb.getUser                         thrpt       3   9.188 ± 5.784  ops/ms
ClientPb.listUser                        thrpt       3   8.047 ± 3.121  ops/ms
ClientPb.createUser                       avgt       3   3.437 ± 1.109   ms/op
ClientPb.existUser                        avgt       3   3.340 ± 0.787   ms/op
ClientPb.getUser                          avgt       3   3.358 ± 0.916   ms/op
ClientPb.listUser                         avgt       3   3.945 ± 0.913   ms/op
ClientPb.createUser                     sample  280327   3.422 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.421           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.367           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.834           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.202           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.734           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.105           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.836           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.031           ms/op
ClientPb.existUser                      sample  291266   3.292 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.417           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.211           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.600           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.944           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.710           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.226           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.543           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.935           ms/op
ClientPb.getUser                        sample  279576   3.434 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.929           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.326           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.903           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.284           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.095           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.193           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.281           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.738           ms/op
ClientPb.listUser                       sample  236200   4.062 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.440           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.924           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.727           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.676           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.778           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.688           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.904           ms/op
