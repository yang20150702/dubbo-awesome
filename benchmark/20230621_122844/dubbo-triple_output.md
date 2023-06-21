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
# Warmup Iteration   1: 2.626 ops/ms
# Warmup Iteration   2: 6.318 ops/ms
# Warmup Iteration   3: 9.150 ops/ms
Iteration   1: 9.710 ops/ms
Iteration   2: 9.961 ops/ms
Iteration   3: 10.004 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.892 ±(99.9%) 2.896 ops/ms [Average]
  (min, avg, max) = (9.710, 9.892, 10.004), stdev = 0.159
  CI (99.9%): [6.996, 12.787] (assumes normal distribution)


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
# Warmup Iteration   1: 3.531 ops/ms
# Warmup Iteration   2: 8.705 ops/ms
# Warmup Iteration   3: 10.123 ops/ms
Iteration   1: 10.350 ops/ms
Iteration   2: 10.006 ops/ms
Iteration   3: 10.442 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.266 ±(99.9%) 4.199 ops/ms [Average]
  (min, avg, max) = (10.006, 10.266, 10.442), stdev = 0.230
  CI (99.9%): [6.067, 14.465] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.647 ops/ms
# Warmup Iteration   2: 9.092 ops/ms
# Warmup Iteration   3: 9.727 ops/ms
Iteration   1: 9.902 ops/ms
Iteration   2: 10.215 ops/ms
Iteration   3: 9.918 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.011 ±(99.9%) 3.213 ops/ms [Average]
  (min, avg, max) = (9.902, 10.011, 10.215), stdev = 0.176
  CI (99.9%): [6.799, 13.224] (assumes normal distribution)


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
# Warmup Iteration   1: 3.039 ops/ms
# Warmup Iteration   2: 7.366 ops/ms
# Warmup Iteration   3: 8.348 ops/ms
Iteration   1: 8.376 ops/ms
Iteration   2: 8.614 ops/ms
Iteration   3: 8.784 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.591 ±(99.9%) 3.732 ops/ms [Average]
  (min, avg, max) = (8.376, 8.591, 8.784), stdev = 0.205
  CI (99.9%): [4.859, 12.323] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.643 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.692 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.264 ±(99.9%) 0.006 ms/op
Iteration   1: 3.128 ±(99.9%) 0.008 ms/op
Iteration   2: 3.210 ±(99.9%) 0.004 ms/op
Iteration   3: 3.132 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.157 ±(99.9%) 0.836 ms/op [Average]
  (min, avg, max) = (3.128, 3.157, 3.210), stdev = 0.046
  CI (99.9%): [2.321, 3.993] (assumes normal distribution)


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
# Warmup Iteration   1: 7.685 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.373 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.005 ms/op
Iteration   1: 3.292 ±(99.9%) 0.002 ms/op
Iteration   2: 3.189 ±(99.9%) 0.004 ms/op
Iteration   3: 3.093 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.191 ±(99.9%) 1.813 ms/op [Average]
  (min, avg, max) = (3.093, 3.191, 3.292), stdev = 0.099
  CI (99.9%): [1.378, 5.005] (assumes normal distribution)


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
# Warmup Iteration   1: 8.272 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.469 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.240 ±(99.9%) 0.003 ms/op
Iteration   1: 3.351 ±(99.9%) 0.003 ms/op
Iteration   2: 3.123 ±(99.9%) 0.007 ms/op
Iteration   3: 3.194 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.223 ±(99.9%) 2.128 ms/op [Average]
  (min, avg, max) = (3.123, 3.223, 3.351), stdev = 0.117
  CI (99.9%): [1.094, 5.351] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.799 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.172 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.924 ±(99.9%) 0.004 ms/op
Iteration   1: 3.637 ±(99.9%) 0.012 ms/op
Iteration   2: 3.711 ±(99.9%) 0.008 ms/op
Iteration   3: 3.825 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.725 ±(99.9%) 1.729 ms/op [Average]
  (min, avg, max) = (3.637, 3.725, 3.825), stdev = 0.095
  CI (99.9%): [1.995, 5.454] (assumes normal distribution)


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
# Warmup Iteration   1: 8.287 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.702 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.221 ±(99.9%) 0.008 ms/op
Iteration   1: 3.161 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.462 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.371 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  17.724 ms/op
                 createUser·p0.9999: 20.436 ms/op
                 createUser·p1.00:   22.020 ms/op

Iteration   2: 3.128 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.509 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.404 ms/op
                 createUser·p0.95:   3.650 ms/op
                 createUser·p0.99:   4.948 ms/op
                 createUser·p0.999:  12.583 ms/op
                 createUser·p0.9999: 22.374 ms/op
                 createUser·p1.00:   23.495 ms/op

Iteration   3: 3.141 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.694 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.310 ms/op
                 createUser·p0.95:   3.621 ms/op
                 createUser·p0.99:   5.480 ms/op
                 createUser·p0.999:  9.686 ms/op
                 createUser·p0.9999: 19.628 ms/op
                 createUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 305004
  mean =      3.143 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19224 
    [ 2.500,  5.000) = 281028 
    [ 5.000,  7.500) = 3792 
    [ 7.500, 10.000) = 538 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 129 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.462 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.359 ms/op
     p(95.0000) =      3.662 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =     15.745 ms/op
     p(99.9900) =     21.807 ms/op
     p(99.9990) =     23.264 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


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
# Warmup Iteration   1: 7.079 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.487 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.118 ±(99.9%) 0.007 ms/op
Iteration   1: 3.116 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.501 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   5.825 ms/op
                 existUser·p0.999:  9.077 ms/op
                 existUser·p0.9999: 20.102 ms/op
                 existUser·p1.00:   20.709 ms/op

Iteration   2: 3.134 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.561 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   5.411 ms/op
                 existUser·p0.999:  8.895 ms/op
                 existUser·p0.9999: 24.373 ms/op
                 existUser·p1.00:   26.182 ms/op

Iteration   3: 3.174 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.963 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   5.784 ms/op
                 existUser·p0.999:  14.565 ms/op
                 existUser·p0.9999: 19.850 ms/op
                 existUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 305448
  mean =      3.141 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21786 
    [ 2.500,  5.000) = 277248 
    [ 5.000,  7.500) = 5329 
    [ 7.500, 10.000) = 540 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 112 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.963 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.355 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     14.427 ms/op
     p(99.9900) =     22.953 ms/op
     p(99.9990) =     25.940 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 8.143 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.541 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.330 ±(99.9%) 0.010 ms/op
Iteration   1: 3.218 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.834 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   4.293 ms/op
                 getUser·p0.99:   6.144 ms/op
                 getUser·p0.999:  11.577 ms/op
                 getUser·p0.9999: 21.137 ms/op
                 getUser·p1.00:   21.922 ms/op

Iteration   2: 3.156 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.046 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.428 ms/op
                 getUser·p0.95:   3.625 ms/op
                 getUser·p0.99:   5.153 ms/op
                 getUser·p0.999:  12.136 ms/op
                 getUser·p0.9999: 36.438 ms/op
                 getUser·p1.00:   37.356 ms/op

Iteration   3: 3.304 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.807 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   4.129 ms/op
                 getUser·p0.99:   5.956 ms/op
                 getUser·p0.999:  13.292 ms/op
                 getUser·p0.9999: 24.780 ms/op
                 getUser·p1.00:   25.985 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297576
  mean =      3.225 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13193 
    [ 2.500,  5.000) = 277921 
    [ 5.000,  7.500) = 5528 
    [ 7.500, 10.000) = 495 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 116 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.957 ms/op
     p(99.0000) =      5.865 ms/op
     p(99.9000) =     12.124 ms/op
     p(99.9900) =     35.209 ms/op
     p(99.9990) =     36.970 ms/op
     p(99.9999) =     37.356 ms/op
    p(100.0000) =     37.356 ms/op


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
# Warmup Iteration   1: 9.099 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.122 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.948 ±(99.9%) 0.013 ms/op
Iteration   1: 3.868 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.167 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.178 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   7.700 ms/op
                 listUser·p0.999:  14.935 ms/op
                 listUser·p0.9999: 22.109 ms/op
                 listUser·p1.00:   23.036 ms/op

Iteration   2: 3.712 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.146 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.178 ms/op
                 listUser·p0.99:   6.570 ms/op
                 listUser·p0.999:  14.645 ms/op
                 listUser·p0.9999: 15.915 ms/op
                 listUser·p1.00:   16.138 ms/op

Iteration   3: 3.796 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.528 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.166 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   7.188 ms/op
                 listUser·p0.999:  14.611 ms/op
                 listUser·p0.9999: 16.443 ms/op
                 listUser·p1.00:   16.712 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253106
  mean =      3.791 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51 
    [ 2.500,  5.000) = 244314 
    [ 5.000,  7.500) = 6578 
    [ 7.500, 10.000) = 1377 
    [10.000, 12.500) = 257 
    [12.500, 15.000) = 314 
    [15.000, 17.500) = 173 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.528 ms/op
     p(50.0000) =      3.666 ms/op
     p(90.0000) =      4.108 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      7.135 ms/op
     p(99.9000) =     14.729 ms/op
     p(99.9900) =     20.591 ms/op
     p(99.9990) =     22.739 ms/op
     p(99.9999) =     23.036 ms/op
    p(100.0000) =     23.036 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.892 ± 2.896  ops/ms
ClientPb.existUser                       thrpt       3  10.266 ± 4.199  ops/ms
ClientPb.getUser                         thrpt       3  10.011 ± 3.213  ops/ms
ClientPb.listUser                        thrpt       3   8.591 ± 3.732  ops/ms
ClientPb.createUser                       avgt       3   3.157 ± 0.836   ms/op
ClientPb.existUser                        avgt       3   3.191 ± 1.813   ms/op
ClientPb.getUser                          avgt       3   3.223 ± 2.128   ms/op
ClientPb.listUser                         avgt       3   3.725 ± 1.729   ms/op
ClientPb.createUser                     sample  305004   3.143 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.462           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.084           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.359           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.662           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.423           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.745           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.807           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.495           ms/op
ClientPb.existUser                      sample  305448   3.141 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.963           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.109           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.355           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.678           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.595           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.427           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.953           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.182           ms/op
ClientPb.getUser                        sample  297576   3.225 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.807           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.133           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.588           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.957           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.865           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.124           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.209           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.356           ms/op
ClientPb.listUser                       sample  253106   3.791 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.528           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.666           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.108           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.135           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.729           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.591           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.036           ms/op
