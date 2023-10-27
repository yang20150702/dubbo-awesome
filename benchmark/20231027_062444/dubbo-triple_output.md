# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.373 ops/ms
# Warmup Iteration   2: 5.969 ops/ms
# Warmup Iteration   3: 9.170 ops/ms
Iteration   1: 9.748 ops/ms
Iteration   2: 9.990 ops/ms
Iteration   3: 9.994 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.911 ±(99.9%) 2.568 ops/ms [Average]
  (min, avg, max) = (9.748, 9.911, 9.994), stdev = 0.141
  CI (99.9%): [7.343, 12.478] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.350 ops/ms
# Warmup Iteration   2: 9.607 ops/ms
# Warmup Iteration   3: 10.041 ops/ms
Iteration   1: 10.456 ops/ms
Iteration   2: 10.100 ops/ms
Iteration   3: 10.484 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.346 ±(99.9%) 3.906 ops/ms [Average]
  (min, avg, max) = (10.100, 10.346, 10.484), stdev = 0.214
  CI (99.9%): [6.440, 14.252] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.587 ops/ms
# Warmup Iteration   2: 9.219 ops/ms
# Warmup Iteration   3: 9.794 ops/ms
Iteration   1: 9.960 ops/ms
Iteration   2: 9.963 ops/ms
Iteration   3: 9.784 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.902 ±(99.9%) 1.876 ops/ms [Average]
  (min, avg, max) = (9.784, 9.902, 9.963), stdev = 0.103
  CI (99.9%): [8.026, 11.778] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.264 ops/ms
# Warmup Iteration   2: 7.618 ops/ms
# Warmup Iteration   3: 8.306 ops/ms
Iteration   1: 8.354 ops/ms
Iteration   2: 8.490 ops/ms
Iteration   3: 8.289 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.378 ±(99.9%) 1.872 ops/ms [Average]
  (min, avg, max) = (8.289, 8.378, 8.490), stdev = 0.103
  CI (99.9%): [6.506, 10.250] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.325 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.579 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.354 ±(99.9%) 0.004 ms/op
Iteration   1: 3.234 ±(99.9%) 0.003 ms/op
Iteration   2: 3.225 ±(99.9%) 0.004 ms/op
Iteration   3: 3.176 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.211 ±(99.9%) 0.574 ms/op [Average]
  (min, avg, max) = (3.176, 3.211, 3.234), stdev = 0.031
  CI (99.9%): [2.638, 3.785] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.374 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.316 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.236 ±(99.9%) 0.004 ms/op
Iteration   1: 3.150 ±(99.9%) 0.002 ms/op
Iteration   2: 3.051 ±(99.9%) 0.003 ms/op
Iteration   3: 3.078 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.093 ±(99.9%) 0.939 ms/op [Average]
  (min, avg, max) = (3.051, 3.093, 3.150), stdev = 0.051
  CI (99.9%): [2.154, 4.031] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.597 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.379 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.254 ±(99.9%) 0.003 ms/op
Iteration   1: 3.257 ±(99.9%) 0.001 ms/op
Iteration   2: 3.144 ±(99.9%) 0.002 ms/op
Iteration   3: 3.251 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.218 ±(99.9%) 1.164 ms/op [Average]
  (min, avg, max) = (3.144, 3.218, 3.257), stdev = 0.064
  CI (99.9%): [2.054, 4.381] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.917 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.137 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.918 ±(99.9%) 0.003 ms/op
Iteration   1: 3.985 ±(99.9%) 0.003 ms/op
Iteration   2: 3.834 ±(99.9%) 0.006 ms/op
Iteration   3: 3.821 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.880 ±(99.9%) 1.665 ms/op [Average]
  (min, avg, max) = (3.821, 3.880, 3.985), stdev = 0.091
  CI (99.9%): [2.215, 5.545] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.891 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.609 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.260 ±(99.9%) 0.009 ms/op
Iteration   1: 3.205 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.407 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   5.259 ms/op
                 createUser·p0.999:  13.249 ms/op
                 createUser·p0.9999: 16.466 ms/op
                 createUser·p1.00:   17.400 ms/op

Iteration   2: 3.241 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.870 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   5.521 ms/op
                 createUser·p0.999:  15.781 ms/op
                 createUser·p0.9999: 18.940 ms/op
                 createUser·p1.00:   20.611 ms/op

Iteration   3: 3.265 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.008 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   6.168 ms/op
                 createUser·p0.999:  15.319 ms/op
                 createUser·p0.9999: 19.857 ms/op
                 createUser·p1.00:   26.378 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296417
  mean =      3.237 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18202 
    [ 2.500,  5.000) = 273573 
    [ 5.000,  7.500) = 3758 
    [ 7.500, 10.000) = 254 
    [10.000, 12.500) = 226 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 148 
    [17.500, 20.000) = 141 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =     15.008 ms/op
     p(99.9900) =     19.202 ms/op
     p(99.9990) =     24.439 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.005 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.446 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.007 ms/op
Iteration   1: 3.162 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.073 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.477 ms/op
                 existUser·p0.95:   3.768 ms/op
                 existUser·p0.99:   5.576 ms/op
                 existUser·p0.999:  10.106 ms/op
                 existUser·p0.9999: 20.054 ms/op
                 existUser·p1.00:   20.578 ms/op

Iteration   2: 3.160 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.004 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   5.718 ms/op
                 existUser·p0.999:  13.722 ms/op
                 existUser·p0.9999: 22.438 ms/op
                 existUser·p1.00:   22.675 ms/op

Iteration   3: 3.093 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.145 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.523 ms/op
                 existUser·p0.99:   5.448 ms/op
                 existUser·p0.999:  13.750 ms/op
                 existUser·p0.9999: 22.206 ms/op
                 existUser·p1.00:   22.643 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 305758
  mean =      3.138 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14982 
    [ 2.500,  5.000) = 285815 
    [ 5.000,  7.500) = 4062 
    [ 7.500, 10.000) = 358 
    [10.000, 12.500) = 200 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 130 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.004 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =     13.635 ms/op
     p(99.9900) =     22.132 ms/op
     p(99.9990) =     22.643 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 8.463 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.412 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.256 ±(99.9%) 0.008 ms/op
Iteration   1: 3.256 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.059 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   6.111 ms/op
                 getUser·p0.999:  15.793 ms/op
                 getUser·p0.9999: 20.302 ms/op
                 getUser·p1.00:   21.758 ms/op

Iteration   2: 3.152 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.100 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.432 ms/op
                 getUser·p0.95:   3.650 ms/op
                 getUser·p0.99:   4.784 ms/op
                 getUser·p0.999:  7.285 ms/op
                 getUser·p0.9999: 23.437 ms/op
                 getUser·p1.00:   23.790 ms/op

Iteration   3: 3.298 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.202 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   6.136 ms/op
                 getUser·p0.999:  15.095 ms/op
                 getUser·p0.9999: 28.812 ms/op
                 getUser·p1.00:   39.059 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296467
  mean =      3.234 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9487 
    [ 2.500,  5.000) = 280706 
    [ 5.000,  7.500) = 5439 
    [ 7.500, 10.000) = 230 
    [10.000, 12.500) = 211 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 112 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =     14.951 ms/op
     p(99.9900) =     24.856 ms/op
     p(99.9990) =     38.802 ms/op
     p(99.9999) =     39.059 ms/op
    p(100.0000) =     39.059 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.177 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 4.185 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.912 ±(99.9%) 0.010 ms/op
Iteration   1: 3.892 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.130 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  15.234 ms/op
                 listUser·p0.9999: 20.407 ms/op
                 listUser·p1.00:   23.691 ms/op

Iteration   2: 3.832 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.544 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.157 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  14.008 ms/op
                 listUser·p0.9999: 17.618 ms/op
                 listUser·p1.00:   18.809 ms/op

Iteration   3: 3.819 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.183 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.170 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   6.848 ms/op
                 listUser·p0.999:  12.358 ms/op
                 listUser·p0.9999: 14.402 ms/op
                 listUser·p1.00:   14.746 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 249355
  mean =      3.847 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 82 
    [ 2.500,  5.000) = 242377 
    [ 5.000,  7.500) = 5287 
    [ 7.500, 10.000) = 832 
    [10.000, 12.500) = 275 
    [12.500, 15.000) = 379 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.544 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      6.832 ms/op
     p(99.9000) =     14.052 ms/op
     p(99.9900) =     17.795 ms/op
     p(99.9990) =     23.398 ms/op
     p(99.9999) =     23.691 ms/op
    p(100.0000) =     23.691 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.911 ± 2.568  ops/ms
ClientPb.existUser                       thrpt       3  10.346 ± 3.906  ops/ms
ClientPb.getUser                         thrpt       3   9.902 ± 1.876  ops/ms
ClientPb.listUser                        thrpt       3   8.378 ± 1.872  ops/ms
ClientPb.createUser                       avgt       3   3.211 ± 0.574   ms/op
ClientPb.existUser                        avgt       3   3.093 ± 0.939   ms/op
ClientPb.getUser                          avgt       3   3.218 ± 1.164   ms/op
ClientPb.listUser                         avgt       3   3.880 ± 1.665   ms/op
ClientPb.createUser                     sample  296417   3.237 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.870           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.604           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.891           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.554           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.008           ms/op
ClientPb.createUser:createUser·p0.9999  sample          19.202           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.378           ms/op
ClientPb.existUser                      sample  305758   3.138 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.004           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.432           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.686           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.612           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.635           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.132           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.675           ms/op
ClientPb.getUser                        sample  296467   3.234 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.059           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.543           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.822           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.833           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.951           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.856           ms/op
ClientPb.getUser:getUser·p1.00          sample          39.059           ms/op
ClientPb.listUser                       sample  249355   3.847 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.544           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.723           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.219           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.832           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.052           ms/op
ClientPb.listUser:listUser·p0.9999      sample          17.795           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.691           ms/op
