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
# Warmup Iteration   1: 2.507 ops/ms
# Warmup Iteration   2: 6.477 ops/ms
# Warmup Iteration   3: 8.985 ops/ms
Iteration   1: 10.019 ops/ms
Iteration   2: 9.685 ops/ms
Iteration   3: 9.756 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.820 ±(99.9%) 3.213 ops/ms [Average]
  (min, avg, max) = (9.685, 9.820, 10.019), stdev = 0.176
  CI (99.9%): [6.607, 13.033] (assumes normal distribution)


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
# Warmup Iteration   1: 3.809 ops/ms
# Warmup Iteration   2: 9.308 ops/ms
# Warmup Iteration   3: 10.182 ops/ms
Iteration   1: 10.420 ops/ms
Iteration   2: 10.677 ops/ms
Iteration   3: 10.416 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.504 ±(99.9%) 2.735 ops/ms [Average]
  (min, avg, max) = (10.416, 10.504, 10.677), stdev = 0.150
  CI (99.9%): [7.769, 13.239] (assumes normal distribution)


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
# Warmup Iteration   1: 3.602 ops/ms
# Warmup Iteration   2: 9.452 ops/ms
# Warmup Iteration   3: 9.924 ops/ms
Iteration   1: 10.190 ops/ms
Iteration   2: 10.141 ops/ms
Iteration   3: 10.039 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.123 ±(99.9%) 1.411 ops/ms [Average]
  (min, avg, max) = (10.039, 10.123, 10.190), stdev = 0.077
  CI (99.9%): [8.713, 11.534] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.400 ops/ms
# Warmup Iteration   2: 8.077 ops/ms
# Warmup Iteration   3: 8.625 ops/ms
Iteration   1: 8.589 ops/ms
Iteration   2: 8.669 ops/ms
Iteration   3: 8.591 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.617 ±(99.9%) 0.836 ops/ms [Average]
  (min, avg, max) = (8.589, 8.617, 8.669), stdev = 0.046
  CI (99.9%): [7.780, 9.453] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.699 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.580 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.261 ±(99.9%) 0.003 ms/op
Iteration   1: 3.184 ±(99.9%) 0.007 ms/op
Iteration   2: 3.159 ±(99.9%) 0.006 ms/op
Iteration   3: 3.146 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.163 ±(99.9%) 0.350 ms/op [Average]
  (min, avg, max) = (3.146, 3.163, 3.184), stdev = 0.019
  CI (99.9%): [2.813, 3.513] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.786 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.412 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.129 ±(99.9%) 0.002 ms/op
Iteration   1: 3.146 ±(99.9%) 0.006 ms/op
Iteration   2: 3.101 ±(99.9%) 0.004 ms/op
Iteration   3: 3.061 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.103 ±(99.9%) 0.773 ms/op [Average]
  (min, avg, max) = (3.061, 3.103, 3.146), stdev = 0.042
  CI (99.9%): [2.329, 3.876] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.461 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.520 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.398 ±(99.9%) 0.006 ms/op
Iteration   1: 3.368 ±(99.9%) 0.005 ms/op
Iteration   2: 3.196 ±(99.9%) 0.007 ms/op
Iteration   3: 3.113 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.226 ±(99.9%) 2.376 ms/op [Average]
  (min, avg, max) = (3.113, 3.226, 3.368), stdev = 0.130
  CI (99.9%): [0.849, 5.602] (assumes normal distribution)


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
# Warmup Iteration   1: 8.384 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.074 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.739 ±(99.9%) 0.008 ms/op
Iteration   1: 3.785 ±(99.9%) 0.005 ms/op
Iteration   2: 3.697 ±(99.9%) 0.007 ms/op
Iteration   3: 3.664 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.715 ±(99.9%) 1.149 ms/op [Average]
  (min, avg, max) = (3.664, 3.715, 3.785), stdev = 0.063
  CI (99.9%): [2.566, 4.864] (assumes normal distribution)


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
# Warmup Iteration   1: 7.909 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.634 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.266 ±(99.9%) 0.009 ms/op
Iteration   1: 3.166 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.075 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  9.879 ms/op
                 createUser·p0.9999: 20.808 ms/op
                 createUser·p1.00:   21.856 ms/op

Iteration   2: 3.243 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.857 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   4.022 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  10.174 ms/op
                 createUser·p0.9999: 26.477 ms/op
                 createUser·p1.00:   27.001 ms/op

Iteration   3: 3.084 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.729 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.228 ms/op
                 createUser·p0.95:   3.293 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  16.077 ms/op
                 createUser·p0.9999: 22.324 ms/op
                 createUser·p1.00:   23.396 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 303173
  mean =      3.163 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23333 
    [ 2.500,  5.000) = 275604 
    [ 5.000,  7.500) = 3495 
    [ 7.500, 10.000) = 382 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 126 
    [20.000, 22.500) = 122 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.857 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =     15.939 ms/op
     p(99.9900) =     24.838 ms/op
     p(99.9990) =     26.706 ms/op
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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.213 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 3.295 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.007 ms/op
Iteration   1: 3.000 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.274 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.191 ms/op
                 existUser·p0.95:   3.416 ms/op
                 existUser·p0.99:   5.333 ms/op
                 existUser·p0.999:  10.156 ms/op
                 existUser·p0.9999: 19.213 ms/op
                 existUser·p1.00:   19.825 ms/op

Iteration   2: 3.068 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.026 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.195 ms/op
                 existUser·p0.95:   3.346 ms/op
                 existUser·p0.99:   5.136 ms/op
                 existUser·p0.999:  11.023 ms/op
                 existUser·p0.9999: 22.958 ms/op
                 existUser·p1.00:   25.625 ms/op

Iteration   3: 3.183 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.202 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.871 ms/op
                 existUser·p0.99:   5.718 ms/op
                 existUser·p0.999:  12.085 ms/op
                 existUser·p0.9999: 19.791 ms/op
                 existUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 311147
  mean =      3.082 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28365 
    [ 2.500,  5.000) = 278002 
    [ 5.000,  7.500) = 3917 
    [ 7.500, 10.000) = 452 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 133 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.026 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.277 ms/op
     p(95.0000) =      3.498 ms/op
     p(99.0000) =      5.349 ms/op
     p(99.9000) =     11.043 ms/op
     p(99.9900) =     21.492 ms/op
     p(99.9990) =     23.786 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


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
# Warmup Iteration   1: 8.127 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.488 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.260 ±(99.9%) 0.009 ms/op
Iteration   1: 3.401 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.987 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.981 ms/op
                 getUser·p0.95:   4.932 ms/op
                 getUser·p0.99:   6.554 ms/op
                 getUser·p0.999:  16.578 ms/op
                 getUser·p0.9999: 18.711 ms/op
                 getUser·p1.00:   20.251 ms/op

Iteration   2: 3.097 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.303 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.371 ms/op
                 getUser·p0.95:   3.539 ms/op
                 getUser·p0.99:   5.325 ms/op
                 getUser·p0.999:  10.811 ms/op
                 getUser·p0.9999: 23.179 ms/op
                 getUser·p1.00:   24.281 ms/op

Iteration   3: 3.159 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.516 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   5.513 ms/op
                 getUser·p0.999:  10.814 ms/op
                 getUser·p0.9999: 21.787 ms/op
                 getUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298532
  mean =      3.214 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14741 
    [ 2.500,  5.000) = 275934 
    [ 5.000,  7.500) = 6936 
    [ 7.500, 10.000) = 479 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.987 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      5.865 ms/op
     p(99.9000) =     13.812 ms/op
     p(99.9900) =     22.348 ms/op
     p(99.9990) =     24.053 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


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
# Warmup Iteration   1: 9.063 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 4.110 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.946 ±(99.9%) 0.012 ms/op
Iteration   1: 3.819 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.013 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.153 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   7.348 ms/op
                 listUser·p0.999:  14.238 ms/op
                 listUser·p0.9999: 20.455 ms/op
                 listUser·p1.00:   21.463 ms/op

Iteration   2: 3.851 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  15.843 ms/op
                 listUser·p0.9999: 20.644 ms/op
                 listUser·p1.00:   20.906 ms/op

Iteration   3: 3.846 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.212 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   6.554 ms/op
                 listUser·p0.999:  11.960 ms/op
                 listUser·p0.9999: 14.582 ms/op
                 listUser·p1.00:   15.860 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 249917
  mean =      3.839 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 240807 
    [ 5.000,  7.500) = 7440 
    [ 7.500, 10.000) = 1034 
    [10.000, 12.500) = 256 
    [12.500, 15.000) = 187 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.013 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     13.615 ms/op
     p(99.9900) =     20.480 ms/op
     p(99.9990) =     20.972 ms/op
     p(99.9999) =     21.463 ms/op
    p(100.0000) =     21.463 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.820 ± 3.213  ops/ms
ClientPb.existUser                       thrpt       3  10.504 ± 2.735  ops/ms
ClientPb.getUser                         thrpt       3  10.123 ± 1.411  ops/ms
ClientPb.listUser                        thrpt       3   8.617 ± 0.836  ops/ms
ClientPb.createUser                       avgt       3   3.163 ± 0.350   ms/op
ClientPb.existUser                        avgt       3   3.103 ± 0.773   ms/op
ClientPb.getUser                          avgt       3   3.226 ± 2.376   ms/op
ClientPb.listUser                         avgt       3   3.715 ± 1.149   ms/op
ClientPb.createUser                     sample  303173   3.163 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.857           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.129           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.453           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.785           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.439           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.939           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.838           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.001           ms/op
ClientPb.existUser                      sample  311147   3.082 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.026           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.277           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.498           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.349           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.043           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.492           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.625           ms/op
ClientPb.getUser                        sample  298532   3.214 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.987           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.633           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.994           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.865           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.812           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.348           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.281           ms/op
ClientPb.listUser                       sample  249917   3.839 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.013           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.736           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.260           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.555           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.906           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.615           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.480           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.463           ms/op
