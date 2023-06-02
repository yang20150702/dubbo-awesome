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
# Warmup Iteration   1: 1.178 ops/ms
# Warmup Iteration   2: 2.786 ops/ms
# Warmup Iteration   3: 5.971 ops/ms
Iteration   1: 5.814 ops/ms
Iteration   2: 6.111 ops/ms
Iteration   3: 6.284 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.069 ±(99.9%) 4.334 ops/ms [Average]
  (min, avg, max) = (5.814, 6.069, 6.284), stdev = 0.238
  CI (99.9%): [1.736, 10.403] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.630 ops/ms
# Warmup Iteration   2: 4.838 ops/ms
# Warmup Iteration   3: 6.324 ops/ms
Iteration   1: 6.628 ops/ms
Iteration   2: 6.505 ops/ms
Iteration   3: 6.672 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.602 ±(99.9%) 1.578 ops/ms [Average]
  (min, avg, max) = (6.505, 6.602, 6.672), stdev = 0.086
  CI (99.9%): [5.024, 8.180] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.758 ops/ms
# Warmup Iteration   2: 4.935 ops/ms
# Warmup Iteration   3: 5.963 ops/ms
Iteration   1: 6.262 ops/ms
Iteration   2: 6.255 ops/ms
Iteration   3: 6.344 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.287 ±(99.9%) 0.908 ops/ms [Average]
  (min, avg, max) = (6.255, 6.287, 6.344), stdev = 0.050
  CI (99.9%): [5.379, 7.195] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.539 ops/ms
# Warmup Iteration   2: 4.195 ops/ms
# Warmup Iteration   3: 5.501 ops/ms
Iteration   1: 5.240 ops/ms
Iteration   2: 5.453 ops/ms
Iteration   3: 5.494 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.396 ±(99.9%) 2.488 ops/ms [Average]
  (min, avg, max) = (5.240, 5.396, 5.494), stdev = 0.136
  CI (99.9%): [2.907, 7.884] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 17.934 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 6.103 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.341 ±(99.9%) 0.008 ms/op
Iteration   1: 5.123 ±(99.9%) 0.014 ms/op
Iteration   2: 5.261 ±(99.9%) 0.011 ms/op
Iteration   3: 5.120 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.168 ±(99.9%) 1.474 ms/op [Average]
  (min, avg, max) = (5.120, 5.168, 5.261), stdev = 0.081
  CI (99.9%): [3.694, 6.643] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 17.622 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 5.763 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.154 ±(99.9%) 0.008 ms/op
Iteration   1: 5.067 ±(99.9%) 0.010 ms/op
Iteration   2: 4.900 ±(99.9%) 0.011 ms/op
Iteration   3: 5.057 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.008 ±(99.9%) 1.707 ms/op [Average]
  (min, avg, max) = (4.900, 5.008, 5.067), stdev = 0.094
  CI (99.9%): [3.301, 6.715] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 18.387 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 5.609 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.158 ±(99.9%) 0.005 ms/op
Iteration   1: 5.073 ±(99.9%) 0.012 ms/op
Iteration   2: 5.248 ±(99.9%) 0.009 ms/op
Iteration   3: 5.117 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.146 ±(99.9%) 1.663 ms/op [Average]
  (min, avg, max) = (5.073, 5.146, 5.248), stdev = 0.091
  CI (99.9%): [3.483, 6.809] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 17.840 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 6.950 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 6.081 ±(99.9%) 0.009 ms/op
Iteration   1: 5.755 ±(99.9%) 0.015 ms/op
Iteration   2: 5.759 ±(99.9%) 0.017 ms/op
Iteration   3: 5.797 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.770 ±(99.9%) 0.428 ms/op [Average]
  (min, avg, max) = (5.755, 5.770, 5.797), stdev = 0.023
  CI (99.9%): [5.343, 6.198] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 17.174 ±(99.9%) 0.293 ms/op
# Warmup Iteration   2: 6.701 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 5.765 ±(99.9%) 0.028 ms/op
Iteration   1: 4.996 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.739 ms/op
                 createUser·p0.50:   4.612 ms/op
                 createUser·p0.90:   6.521 ms/op
                 createUser·p0.95:   7.438 ms/op
                 createUser·p0.99:   10.404 ms/op
                 createUser·p0.999:  22.560 ms/op
                 createUser·p0.9999: 29.150 ms/op
                 createUser·p1.00:   32.440 ms/op

Iteration   2: 5.063 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.948 ms/op
                 createUser·p0.50:   4.719 ms/op
                 createUser·p0.90:   6.447 ms/op
                 createUser·p0.95:   7.414 ms/op
                 createUser·p0.99:   10.387 ms/op
                 createUser·p0.999:  24.380 ms/op
                 createUser·p0.9999: 29.950 ms/op
                 createUser·p1.00:   30.540 ms/op

Iteration   3: 5.077 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.694 ms/op
                 createUser·p0.50:   4.743 ms/op
                 createUser·p0.90:   6.390 ms/op
                 createUser·p0.95:   7.266 ms/op
                 createUser·p0.99:   9.617 ms/op
                 createUser·p0.999:  25.329 ms/op
                 createUser·p0.9999: 31.548 ms/op
                 createUser·p1.00:   32.997 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 190304
  mean =      5.045 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60 
    [ 2.500,  5.000) = 131302 
    [ 5.000,  7.500) = 50202 
    [ 7.500, 10.000) = 6716 
    [10.000, 12.500) = 1229 
    [12.500, 15.000) = 447 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 88 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.694 ms/op
     p(50.0000) =      4.678 ms/op
     p(90.0000) =      6.447 ms/op
     p(95.0000) =      7.373 ms/op
     p(99.0000) =     10.158 ms/op
     p(99.9000) =     22.708 ms/op
     p(99.9900) =     30.048 ms/op
     p(99.9990) =     32.494 ms/op
     p(99.9999) =     32.997 ms/op
    p(100.0000) =     32.997 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 15.429 ±(99.9%) 0.240 ms/op
# Warmup Iteration   2: 5.493 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.072 ±(99.9%) 0.020 ms/op
Iteration   1: 5.127 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.030 ms/op
                 existUser·p0.50:   4.727 ms/op
                 existUser·p0.90:   6.570 ms/op
                 existUser·p0.95:   7.660 ms/op
                 existUser·p0.99:   10.191 ms/op
                 existUser·p0.999:  22.816 ms/op
                 existUser·p0.9999: 34.144 ms/op
                 existUser·p1.00:   34.865 ms/op

Iteration   2: 4.990 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.355 ms/op
                 existUser·p0.50:   4.620 ms/op
                 existUser·p0.90:   6.308 ms/op
                 existUser·p0.95:   7.471 ms/op
                 existUser·p0.99:   10.043 ms/op
                 existUser·p0.999:  23.546 ms/op
                 existUser·p0.9999: 34.103 ms/op
                 existUser·p1.00:   35.127 ms/op

Iteration   3: 5.058 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.183 ms/op
                 existUser·p0.50:   4.678 ms/op
                 existUser·p0.90:   6.447 ms/op
                 existUser·p0.95:   7.569 ms/op
                 existUser·p0.99:   10.076 ms/op
                 existUser·p0.999:  27.420 ms/op
                 existUser·p0.9999: 34.123 ms/op
                 existUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 189639
  mean =      5.058 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42 
    [ 2.500,  5.000) = 128453 
    [ 5.000,  7.500) = 51192 
    [ 7.500, 10.000) = 7966 
    [10.000, 12.500) = 1286 
    [12.500, 15.000) = 338 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 65 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.030 ms/op
     p(50.0000) =      4.669 ms/op
     p(90.0000) =      6.447 ms/op
     p(95.0000) =      7.569 ms/op
     p(99.0000) =     10.093 ms/op
     p(99.9000) =     22.863 ms/op
     p(99.9900) =     34.144 ms/op
     p(99.9990) =     34.892 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


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
# Warmup Iteration   1: 17.569 ±(99.9%) 0.259 ms/op
# Warmup Iteration   2: 6.215 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.409 ±(99.9%) 0.023 ms/op
Iteration   1: 5.173 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.347 ms/op
                 getUser·p0.50:   4.858 ms/op
                 getUser·p0.90:   6.390 ms/op
                 getUser·p0.95:   7.373 ms/op
                 getUser·p0.99:   10.050 ms/op
                 getUser·p0.999:  21.917 ms/op
                 getUser·p0.9999: 31.931 ms/op
                 getUser·p1.00:   34.341 ms/op

Iteration   2: 5.292 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.171 ms/op
                 getUser·p0.50:   4.858 ms/op
                 getUser·p0.90:   6.685 ms/op
                 getUser·p0.95:   8.266 ms/op
                 getUser·p0.99:   11.960 ms/op
                 getUser·p0.999:  24.510 ms/op
                 getUser·p0.9999: 28.465 ms/op
                 getUser·p1.00:   30.835 ms/op

Iteration   3: 5.120 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.063 ms/op
                 getUser·p0.50:   4.809 ms/op
                 getUser·p0.90:   6.226 ms/op
                 getUser·p0.95:   7.201 ms/op
                 getUser·p0.99:   10.371 ms/op
                 getUser·p0.999:  24.186 ms/op
                 getUser·p0.9999: 28.475 ms/op
                 getUser·p1.00:   29.098 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 184637
  mean =      5.194 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 109648 
    [ 5.000,  7.500) = 65271 
    [ 7.500, 10.000) = 7020 
    [10.000, 12.500) = 1710 
    [12.500, 15.000) = 596 
    [15.000, 17.500) = 160 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.063 ms/op
     p(50.0000) =      4.841 ms/op
     p(90.0000) =      6.423 ms/op
     p(95.0000) =      7.586 ms/op
     p(99.0000) =     10.813 ms/op
     p(99.9000) =     22.872 ms/op
     p(99.9900) =     30.870 ms/op
     p(99.9990) =     34.230 ms/op
     p(99.9999) =     34.341 ms/op
    p(100.0000) =     34.341 ms/op


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
# Warmup Iteration   1: 18.700 ±(99.9%) 0.323 ms/op
# Warmup Iteration   2: 6.891 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 6.058 ±(99.9%) 0.029 ms/op
Iteration   1: 6.002 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.814 ms/op
                 listUser·p0.50:   5.595 ms/op
                 listUser·p0.90:   7.497 ms/op
                 listUser·p0.95:   8.765 ms/op
                 listUser·p0.99:   11.649 ms/op
                 listUser·p0.999:  25.494 ms/op
                 listUser·p0.9999: 28.161 ms/op
                 listUser·p1.00:   35.717 ms/op

Iteration   2: 5.878 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   3.232 ms/op
                 listUser·p0.50:   5.415 ms/op
                 listUser·p0.90:   7.438 ms/op
                 listUser·p0.95:   8.520 ms/op
                 listUser·p0.99:   11.420 ms/op
                 listUser·p0.999:  26.935 ms/op
                 listUser·p0.9999: 29.888 ms/op
                 listUser·p1.00:   30.409 ms/op

Iteration   3: 5.885 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.960 ms/op
                 listUser·p0.50:   5.505 ms/op
                 listUser·p0.90:   7.324 ms/op
                 listUser·p0.95:   8.495 ms/op
                 listUser·p0.99:   11.012 ms/op
                 listUser·p0.999:  22.479 ms/op
                 listUser·p0.9999: 30.433 ms/op
                 listUser·p1.00:   32.014 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 162049
  mean =      5.921 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 22350 
    [ 5.000,  7.500) = 124166 
    [ 7.500, 10.000) = 12209 
    [10.000, 12.500) = 2286 
    [12.500, 15.000) = 495 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 137 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 100 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.960 ms/op
     p(50.0000) =      5.505 ms/op
     p(90.0000) =      7.430 ms/op
     p(95.0000) =      8.585 ms/op
     p(99.0000) =     11.420 ms/op
     p(99.9000) =     25.000 ms/op
     p(99.9900) =     29.819 ms/op
     p(99.9990) =     33.420 ms/op
     p(99.9999) =     35.717 ms/op
    p(100.0000) =     35.717 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.069 ± 4.334  ops/ms
ClientPb.existUser                       thrpt       3   6.602 ± 1.578  ops/ms
ClientPb.getUser                         thrpt       3   6.287 ± 0.908  ops/ms
ClientPb.listUser                        thrpt       3   5.396 ± 2.488  ops/ms
ClientPb.createUser                       avgt       3   5.168 ± 1.474   ms/op
ClientPb.existUser                        avgt       3   5.008 ± 1.707   ms/op
ClientPb.getUser                          avgt       3   5.146 ± 1.663   ms/op
ClientPb.listUser                         avgt       3   5.770 ± 0.428   ms/op
ClientPb.createUser                     sample  190304   5.045 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.694           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.678           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.447           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.373           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.158           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.708           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.048           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.997           ms/op
ClientPb.existUser                      sample  189639   5.058 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.030           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.669           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.447           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.569           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.093           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.863           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.144           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.127           ms/op
ClientPb.getUser                        sample  184637   5.194 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.063           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.841           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.423           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.586           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.813           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.872           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.870           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.341           ms/op
ClientPb.listUser                       sample  162049   5.921 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.960           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.505           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.430           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.585           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.420           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.000           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.819           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.717           ms/op
