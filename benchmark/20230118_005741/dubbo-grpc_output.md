# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.234 ops/ms
# Warmup Iteration   2: 8.897 ops/ms
# Warmup Iteration   3: 10.125 ops/ms
Iteration   1: 10.205 ops/ms
Iteration   2: 10.260 ops/ms
Iteration   3: 9.910 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.125 ±(99.9%) 3.437 ops/ms [Average]
  (min, avg, max) = (9.910, 10.125, 10.260), stdev = 0.188
  CI (99.9%): [6.688, 13.563] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.567 ops/ms
# Warmup Iteration   2: 10.438 ops/ms
# Warmup Iteration   3: 10.546 ops/ms
Iteration   1: 10.708 ops/ms
Iteration   2: 10.626 ops/ms
Iteration   3: 10.384 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.572 ±(99.9%) 3.072 ops/ms [Average]
  (min, avg, max) = (10.384, 10.572, 10.708), stdev = 0.168
  CI (99.9%): [7.500, 13.645] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.762 ops/ms
# Warmup Iteration   2: 9.914 ops/ms
# Warmup Iteration   3: 10.275 ops/ms
Iteration   1: 10.432 ops/ms
Iteration   2: 10.172 ops/ms
Iteration   3: 10.020 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.208 ±(99.9%) 3.802 ops/ms [Average]
  (min, avg, max) = (10.020, 10.208, 10.432), stdev = 0.208
  CI (99.9%): [6.406, 14.010] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.732 ops/ms
# Warmup Iteration   2: 7.683 ops/ms
# Warmup Iteration   3: 7.837 ops/ms
Iteration   1: 7.967 ops/ms
Iteration   2: 8.009 ops/ms
Iteration   3: 7.990 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.989 ±(99.9%) 0.390 ops/ms [Average]
  (min, avg, max) = (7.967, 7.989, 8.009), stdev = 0.021
  CI (99.9%): [7.599, 8.378] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.228 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.197 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.107 ±(99.9%) 0.003 ms/op
Iteration   1: 3.195 ±(99.9%) 0.002 ms/op
Iteration   2: 3.084 ±(99.9%) 0.002 ms/op
Iteration   3: 3.007 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.095 ±(99.9%) 1.719 ms/op [Average]
  (min, avg, max) = (3.007, 3.095, 3.195), stdev = 0.094
  CI (99.9%): [1.377, 4.814] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.844 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.956 ±(99.9%) 0.003 ms/op
Iteration   1: 3.011 ±(99.9%) 0.003 ms/op
Iteration   2: 3.046 ±(99.9%) 0.002 ms/op
Iteration   3: 2.945 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.001 ±(99.9%) 0.927 ms/op [Average]
  (min, avg, max) = (2.945, 3.001, 3.046), stdev = 0.051
  CI (99.9%): [2.074, 3.927] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.256 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.315 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.108 ±(99.9%) 0.003 ms/op
Iteration   1: 3.100 ±(99.9%) 0.002 ms/op
Iteration   2: 3.138 ±(99.9%) 0.003 ms/op
Iteration   3: 3.100 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.113 ±(99.9%) 0.396 ms/op [Average]
  (min, avg, max) = (3.100, 3.113, 3.138), stdev = 0.022
  CI (99.9%): [2.716, 3.509] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.018 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.349 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.179 ±(99.9%) 0.024 ms/op
Iteration   1: 4.161 ±(99.9%) 0.024 ms/op
Iteration   2: 4.095 ±(99.9%) 0.014 ms/op
Iteration   3: 4.130 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.129 ±(99.9%) 0.604 ms/op [Average]
  (min, avg, max) = (4.095, 4.129, 4.161), stdev = 0.033
  CI (99.9%): [3.525, 4.733] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.936 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.175 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.006 ms/op
Iteration   1: 3.141 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.693 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  6.824 ms/op
                 createUser·p0.9999: 11.331 ms/op
                 createUser·p1.00:   12.517 ms/op

Iteration   2: 3.141 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.578 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  7.776 ms/op
                 createUser·p0.9999: 13.219 ms/op
                 createUser·p1.00:   13.451 ms/op

Iteration   3: 3.199 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.739 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  11.928 ms/op
                 createUser·p0.9999: 26.608 ms/op
                 createUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304000
  mean =      3.160 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17584 
    [ 2.500,  5.000) = 285417 
    [ 5.000,  7.500) = 634 
    [ 7.500, 10.000) = 98 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.578 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      4.026 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      8.585 ms/op
     p(99.9900) =     24.864 ms/op
     p(99.9990) =     26.899 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.950 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.022 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.869 ±(99.9%) 0.007 ms/op
Iteration   1: 2.950 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.602 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  8.663 ms/op
                 existUser·p0.9999: 15.892 ms/op
                 existUser·p1.00:   17.302 ms/op

Iteration   2: 3.030 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.717 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   3.879 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  9.044 ms/op
                 existUser·p0.9999: 16.013 ms/op
                 existUser·p1.00:   17.105 ms/op

Iteration   3: 2.876 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.669 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.482 ms/op
                 existUser·p0.99:   4.319 ms/op
                 existUser·p0.999:  6.688 ms/op
                 existUser·p0.9999: 30.835 ms/op
                 existUser·p1.00:   30.867 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325281
  mean =      2.951 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40583 
    [ 2.500,  5.000) = 283689 
    [ 5.000,  7.500) = 617 
    [ 7.500, 10.000) = 171 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.602 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      8.351 ms/op
     p(99.9900) =     26.041 ms/op
     p(99.9990) =     30.867 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.111 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.174 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.100 ±(99.9%) 0.006 ms/op
Iteration   1: 3.161 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.780 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   4.026 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  7.665 ms/op
                 getUser·p0.9999: 12.301 ms/op
                 getUser·p1.00:   12.599 ms/op

Iteration   2: 3.201 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.583 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.928 ms/op
                 getUser·p0.95:   4.125 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  6.104 ms/op
                 getUser·p0.9999: 13.976 ms/op
                 getUser·p1.00:   14.369 ms/op

Iteration   3: 3.050 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.642 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  6.750 ms/op
                 getUser·p0.9999: 14.836 ms/op
                 getUser·p1.00:   16.482 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306036
  mean =      3.136 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1175 
    [ 1.250,  2.500) = 18369 
    [ 2.500,  3.750) = 253493 
    [ 3.750,  5.000) = 32003 
    [ 5.000,  6.250) = 573 
    [ 6.250,  7.500) = 223 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 21 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 67 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.583 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.002 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      6.652 ms/op
     p(99.9900) =     14.500 ms/op
     p(99.9990) =     16.380 ms/op
     p(99.9999) =     16.482 ms/op
    p(100.0000) =     16.482 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.460 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.153 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.144 ±(99.9%) 0.011 ms/op
Iteration   1: 4.148 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.233 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   5.423 ms/op
                 listUser·p0.95:   5.947 ms/op
                 listUser·p0.99:   7.356 ms/op
                 listUser·p0.999:  13.238 ms/op
                 listUser·p0.9999: 23.045 ms/op
                 listUser·p1.00:   23.921 ms/op

Iteration   2: 4.005 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.145 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  14.882 ms/op
                 listUser·p0.9999: 20.579 ms/op
                 listUser·p1.00:   20.972 ms/op

Iteration   3: 4.101 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.212 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.366 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  14.975 ms/op
                 listUser·p0.9999: 16.682 ms/op
                 listUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235033
  mean =      4.084 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3426 
    [ 2.500,  5.000) = 197684 
    [ 5.000,  7.500) = 32342 
    [ 7.500, 10.000) = 1129 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 170 
    [15.000, 17.500) = 133 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.145 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      5.341 ms/op
     p(95.0000) =      5.874 ms/op
     p(99.0000) =      7.111 ms/op
     p(99.9000) =     14.254 ms/op
     p(99.9900) =     22.282 ms/op
     p(99.9990) =     23.775 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.125 ± 3.437  ops/ms
ClientGrpc.existUser                       thrpt       3  10.572 ± 3.072  ops/ms
ClientGrpc.getUser                         thrpt       3  10.208 ± 3.802  ops/ms
ClientGrpc.listUser                        thrpt       3   7.989 ± 0.390  ops/ms
ClientGrpc.createUser                       avgt       3   3.095 ± 1.719   ms/op
ClientGrpc.existUser                        avgt       3   3.001 ± 0.927   ms/op
ClientGrpc.getUser                          avgt       3   3.113 ± 0.396   ms/op
ClientGrpc.listUser                         avgt       3   4.129 ± 0.604   ms/op
ClientGrpc.createUser                     sample  304000   3.160 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.578           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.142           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.785           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.026           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.585           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.864           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.903           ms/op
ClientGrpc.existUser                      sample  325281   2.951 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.602           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.949           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.514           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.756           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.243           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.351           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.041           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          30.867           ms/op
ClientGrpc.getUser                        sample  306036   3.136 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.583           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.125           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.777           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.002           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.432           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.652           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.500           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.482           ms/op
ClientGrpc.listUser                       sample  235033   4.084 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.145           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.891           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.341           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.874           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.111           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.254           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.282           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.921           ms/op
