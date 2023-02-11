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
# Warmup Iteration   1: 2.662 ops/ms
# Warmup Iteration   2: 6.629 ops/ms
# Warmup Iteration   3: 9.784 ops/ms
Iteration   1: 10.067 ops/ms
Iteration   2: 9.768 ops/ms
Iteration   3: 10.129 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.988 ±(99.9%) 3.514 ops/ms [Average]
  (min, avg, max) = (9.768, 9.988, 10.129), stdev = 0.193
  CI (99.9%): [6.474, 13.502] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.428 ops/ms
# Warmup Iteration   2: 8.994 ops/ms
# Warmup Iteration   3: 9.565 ops/ms
Iteration   1: 10.251 ops/ms
Iteration   2: 10.438 ops/ms
Iteration   3: 10.283 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.324 ±(99.9%) 1.823 ops/ms [Average]
  (min, avg, max) = (10.251, 10.324, 10.438), stdev = 0.100
  CI (99.9%): [8.501, 12.147] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.061 ops/ms
# Warmup Iteration   2: 9.529 ops/ms
# Warmup Iteration   3: 10.011 ops/ms
Iteration   1: 10.436 ops/ms
Iteration   2: 10.215 ops/ms
Iteration   3: 10.097 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.250 ±(99.9%) 3.140 ops/ms [Average]
  (min, avg, max) = (10.097, 10.250, 10.436), stdev = 0.172
  CI (99.9%): [7.109, 13.390] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.391 ops/ms
# Warmup Iteration   2: 8.069 ops/ms
# Warmup Iteration   3: 8.758 ops/ms
Iteration   1: 8.647 ops/ms
Iteration   2: 8.740 ops/ms
Iteration   3: 8.539 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.642 ±(99.9%) 1.835 ops/ms [Average]
  (min, avg, max) = (8.539, 8.642, 8.740), stdev = 0.101
  CI (99.9%): [6.807, 10.477] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.907 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.874 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.354 ±(99.9%) 0.002 ms/op
Iteration   1: 3.248 ±(99.9%) 0.003 ms/op
Iteration   2: 3.118 ±(99.9%) 0.006 ms/op
Iteration   3: 3.113 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.160 ±(99.9%) 1.400 ms/op [Average]
  (min, avg, max) = (3.113, 3.160, 3.248), stdev = 0.077
  CI (99.9%): [1.760, 4.560] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.189 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.243 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.002 ms/op
Iteration   1: 3.077 ±(99.9%) 0.004 ms/op
Iteration   2: 3.013 ±(99.9%) 0.003 ms/op
Iteration   3: 2.986 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.026 ±(99.9%) 0.851 ms/op [Average]
  (min, avg, max) = (2.986, 3.026, 3.077), stdev = 0.047
  CI (99.9%): [2.175, 3.876] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.459 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.498 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.328 ±(99.9%) 0.006 ms/op
Iteration   1: 3.081 ±(99.9%) 0.006 ms/op
Iteration   2: 3.221 ±(99.9%) 0.003 ms/op
Iteration   3: 3.083 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.129 ±(99.9%) 1.462 ms/op [Average]
  (min, avg, max) = (3.081, 3.129, 3.221), stdev = 0.080
  CI (99.9%): [1.667, 4.591] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.200 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.931 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.749 ±(99.9%) 0.009 ms/op
Iteration   1: 3.621 ±(99.9%) 0.010 ms/op
Iteration   2: 3.833 ±(99.9%) 0.006 ms/op
Iteration   3: 3.725 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.726 ±(99.9%) 1.930 ms/op [Average]
  (min, avg, max) = (3.621, 3.726, 3.833), stdev = 0.106
  CI (99.9%): [1.796, 5.656] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.994 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.615 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.198 ±(99.9%) 0.008 ms/op
Iteration   1: 3.188 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.087 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   5.399 ms/op
                 createUser·p0.999:  11.970 ms/op
                 createUser·p0.9999: 17.918 ms/op
                 createUser·p1.00:   18.547 ms/op

Iteration   2: 3.220 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.323 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   4.121 ms/op
                 createUser·p0.99:   5.882 ms/op
                 createUser·p0.999:  18.121 ms/op
                 createUser·p0.9999: 21.205 ms/op
                 createUser·p1.00:   21.758 ms/op

Iteration   3: 3.180 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.452 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   4.784 ms/op
                 createUser·p0.999:  18.514 ms/op
                 createUser·p0.9999: 20.283 ms/op
                 createUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300413
  mean =      3.196 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19866 
    [ 2.500,  5.000) = 275368 
    [ 5.000,  7.500) = 4090 
    [ 7.500, 10.000) = 501 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 221 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.940 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =     17.026 ms/op
     p(99.9900) =     20.283 ms/op
     p(99.9990) =     21.659 ms/op
     p(99.9999) =     21.758 ms/op
    p(100.0000) =     21.758 ms/op


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
# Warmup Iteration   1: 7.945 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.462 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.195 ±(99.9%) 0.007 ms/op
Iteration   1: 3.149 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.993 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  11.557 ms/op
                 existUser·p0.9999: 18.973 ms/op
                 existUser·p1.00:   19.464 ms/op

Iteration   2: 3.145 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.509 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.686 ms/op
                 existUser·p0.95:   3.916 ms/op
                 existUser·p0.99:   5.977 ms/op
                 existUser·p0.999:  8.738 ms/op
                 existUser·p0.9999: 20.703 ms/op
                 existUser·p1.00:   21.823 ms/op

Iteration   3: 3.123 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.225 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.723 ms/op
                 existUser·p0.95:   4.129 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  8.602 ms/op
                 existUser·p0.9999: 21.594 ms/op
                 existUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 305900
  mean =      3.139 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22892 
    [ 2.500,  5.000) = 276798 
    [ 5.000,  7.500) = 5388 
    [ 7.500, 10.000) = 481 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 145 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.993 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     10.895 ms/op
     p(99.9900) =     21.004 ms/op
     p(99.9990) =     21.953 ms/op
     p(99.9999) =     22.446 ms/op
    p(100.0000) =     22.446 ms/op


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
# Warmup Iteration   1: 9.242 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.638 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.304 ±(99.9%) 0.010 ms/op
Iteration   1: 3.270 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.141 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   4.043 ms/op
                 getUser·p0.99:   6.554 ms/op
                 getUser·p0.999:  17.469 ms/op
                 getUser·p0.9999: 19.176 ms/op
                 getUser·p1.00:   21.594 ms/op

Iteration   2: 3.204 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.350 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   4.170 ms/op
                 getUser·p0.99:   5.579 ms/op
                 getUser·p0.999:  10.797 ms/op
                 getUser·p0.9999: 23.168 ms/op
                 getUser·p1.00:   23.265 ms/op

Iteration   3: 3.156 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.549 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   5.317 ms/op
                 getUser·p0.999:  11.906 ms/op
                 getUser·p0.9999: 23.529 ms/op
                 getUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299032
  mean =      3.209 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24341 
    [ 2.500,  5.000) = 267435 
    [ 5.000,  7.500) = 6249 
    [ 7.500, 10.000) = 564 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 192 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.549 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     17.170 ms/op
     p(99.9900) =     22.957 ms/op
     p(99.9990) =     24.020 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


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
# Warmup Iteration   1: 9.293 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 4.479 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.891 ±(99.9%) 0.013 ms/op
Iteration   1: 3.763 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.167 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.035 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  17.793 ms/op
                 listUser·p0.9999: 20.283 ms/op
                 listUser·p1.00:   21.463 ms/op

Iteration   2: 3.665 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.154 ms/op
                 listUser·p0.50:   3.568 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.104 ms/op
                 listUser·p0.99:   6.480 ms/op
                 listUser·p0.999:  13.227 ms/op
                 listUser·p0.9999: 15.037 ms/op
                 listUser·p1.00:   15.188 ms/op

Iteration   3: 3.672 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   1.845 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.096 ms/op
                 listUser·p0.99:   6.300 ms/op
                 listUser·p0.999:  12.616 ms/op
                 listUser·p0.9999: 13.276 ms/op
                 listUser·p1.00:   15.335 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 259547
  mean =      3.699 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 89 
    [ 2.500,  5.000) = 253606 
    [ 5.000,  7.500) = 4546 
    [ 7.500, 10.000) = 652 
    [10.000, 12.500) = 249 
    [12.500, 15.000) = 257 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.162 ms/op
     p(99.0000) =      6.521 ms/op
     p(99.9000) =     13.058 ms/op
     p(99.9900) =     19.272 ms/op
     p(99.9990) =     21.293 ms/op
     p(99.9999) =     21.463 ms/op
    p(100.0000) =     21.463 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.988 ± 3.514  ops/ms
ClientPb.existUser                       thrpt       3  10.324 ± 1.823  ops/ms
ClientPb.getUser                         thrpt       3  10.250 ± 3.140  ops/ms
ClientPb.listUser                        thrpt       3   8.642 ± 1.835  ops/ms
ClientPb.createUser                       avgt       3   3.160 ± 1.400   ms/op
ClientPb.existUser                        avgt       3   3.026 ± 0.851   ms/op
ClientPb.getUser                          avgt       3   3.129 ± 1.462   ms/op
ClientPb.listUser                         avgt       3   3.726 ± 1.930   ms/op
ClientPb.createUser                     sample  300413   3.196 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.087           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.613           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.940           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.415           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.026           ms/op
ClientPb.createUser:createUser·p0.9999  sample          20.283           ms/op
ClientPb.createUser:createUser·p1.00    sample          21.758           ms/op
ClientPb.existUser                      sample  305900   3.139 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.993           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.580           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.998           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.661           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.895           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.004           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.446           ms/op
ClientPb.getUser                        sample  299032   3.209 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.549           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.629           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.014           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.792           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.170           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.957           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.117           ms/op
ClientPb.listUser                       sample  259547   3.699 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.167           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.621           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.961           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.162           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.521           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.058           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.272           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.463           ms/op
