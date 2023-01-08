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
# Warmup Iteration   1: 5.065 ops/ms
# Warmup Iteration   2: 9.656 ops/ms
# Warmup Iteration   3: 10.762 ops/ms
Iteration   1: 10.489 ops/ms
Iteration   2: 10.460 ops/ms
Iteration   3: 10.469 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.473 ±(99.9%) 0.271 ops/ms [Average]
  (min, avg, max) = (10.460, 10.473, 10.489), stdev = 0.015
  CI (99.9%): [10.202, 10.744] (assumes normal distribution)


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
# Warmup Iteration   1: 8.285 ops/ms
# Warmup Iteration   2: 10.726 ops/ms
# Warmup Iteration   3: 11.127 ops/ms
Iteration   1: 11.073 ops/ms
Iteration   2: 11.022 ops/ms
Iteration   3: 11.140 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.078 ±(99.9%) 1.076 ops/ms [Average]
  (min, avg, max) = (11.022, 11.078, 11.140), stdev = 0.059
  CI (99.9%): [10.002, 12.154] (assumes normal distribution)


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
# Warmup Iteration   1: 8.589 ops/ms
# Warmup Iteration   2: 10.327 ops/ms
# Warmup Iteration   3: 10.533 ops/ms
Iteration   1: 10.428 ops/ms
Iteration   2: 10.366 ops/ms
Iteration   3: 10.573 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.456 ±(99.9%) 1.934 ops/ms [Average]
  (min, avg, max) = (10.366, 10.456, 10.573), stdev = 0.106
  CI (99.9%): [8.521, 12.390] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.714 ops/ms
# Warmup Iteration   2: 7.713 ops/ms
# Warmup Iteration   3: 8.093 ops/ms
Iteration   1: 7.972 ops/ms
Iteration   2: 7.990 ops/ms
Iteration   3: 8.075 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.012 ±(99.9%) 1.010 ops/ms [Average]
  (min, avg, max) = (7.972, 8.012, 8.075), stdev = 0.055
  CI (99.9%): [7.003, 9.022] (assumes normal distribution)


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
# Warmup Iteration   1: 3.915 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.002 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.062 ±(99.9%) 0.003 ms/op
Iteration   1: 3.146 ±(99.9%) 0.012 ms/op
Iteration   2: 3.075 ±(99.9%) 0.002 ms/op
Iteration   3: 3.073 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.098 ±(99.9%) 0.752 ms/op [Average]
  (min, avg, max) = (3.073, 3.098, 3.146), stdev = 0.041
  CI (99.9%): [2.346, 3.850] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.708 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.942 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.942 ±(99.9%) 0.003 ms/op
Iteration   1: 2.904 ±(99.9%) 0.003 ms/op
Iteration   2: 2.915 ±(99.9%) 0.004 ms/op
Iteration   3: 2.956 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.925 ±(99.9%) 0.503 ms/op [Average]
  (min, avg, max) = (2.904, 2.925, 2.956), stdev = 0.028
  CI (99.9%): [2.422, 3.428] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.754 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.985 ±(99.9%) 0.004 ms/op
Iteration   1: 3.014 ±(99.9%) 0.002 ms/op
Iteration   2: 2.957 ±(99.9%) 0.004 ms/op
Iteration   3: 3.019 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.997 ±(99.9%) 0.627 ms/op [Average]
  (min, avg, max) = (2.957, 2.997, 3.019), stdev = 0.034
  CI (99.9%): [2.370, 3.624] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.133 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.044 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.868 ±(99.9%) 0.022 ms/op
Iteration   1: 4.038 ±(99.9%) 0.028 ms/op
Iteration   2: 3.957 ±(99.9%) 0.034 ms/op
Iteration   3: 4.177 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.057 ±(99.9%) 2.033 ms/op [Average]
  (min, avg, max) = (3.957, 4.057, 4.177), stdev = 0.111
  CI (99.9%): [2.024, 6.090] (assumes normal distribution)


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
# Warmup Iteration   1: 3.794 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.143 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.999 ±(99.9%) 0.006 ms/op
Iteration   1: 3.133 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.812 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  6.274 ms/op
                 createUser·p0.9999: 22.774 ms/op
                 createUser·p1.00:   23.069 ms/op

Iteration   2: 3.114 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.752 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  7.997 ms/op
                 createUser·p0.9999: 16.473 ms/op
                 createUser·p1.00:   16.712 ms/op

Iteration   3: 3.148 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.690 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  10.981 ms/op
                 createUser·p0.9999: 20.239 ms/op
                 createUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306584
  mean =      3.132 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24713 
    [ 2.500,  5.000) = 280941 
    [ 5.000,  7.500) = 592 
    [ 7.500, 10.000) = 82 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      7.971 ms/op
     p(99.9900) =     22.130 ms/op
     p(99.9990) =     22.970 ms/op
     p(99.9999) =     23.069 ms/op
    p(100.0000) =     23.069 ms/op


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
# Warmup Iteration   1: 3.720 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.952 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.887 ±(99.9%) 0.006 ms/op
Iteration   1: 2.859 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.417 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  6.939 ms/op
                 existUser·p0.9999: 11.158 ms/op
                 existUser·p1.00:   11.289 ms/op

Iteration   2: 2.922 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.522 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.641 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   4.082 ms/op
                 existUser·p0.999:  8.421 ms/op
                 existUser·p0.9999: 14.896 ms/op
                 existUser·p1.00:   15.204 ms/op

Iteration   3: 2.896 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.549 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  6.193 ms/op
                 existUser·p0.9999: 18.283 ms/op
                 existUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331855
  mean =      2.892 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3700 
    [ 1.250,  2.500) = 55165 
    [ 2.500,  3.750) = 257279 
    [ 3.750,  5.000) = 14844 
    [ 5.000,  6.250) = 455 
    [ 6.250,  7.500) = 139 
    [ 7.500,  8.750) = 76 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 43 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.417 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      6.932 ms/op
     p(99.9900) =     15.195 ms/op
     p(99.9990) =     18.559 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


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
# Warmup Iteration   1: 3.891 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.095 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.007 ms/op
Iteration   1: 3.002 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.742 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  6.488 ms/op
                 getUser·p0.9999: 14.986 ms/op
                 getUser·p1.00:   15.270 ms/op

Iteration   2: 2.974 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.216 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.400 ms/op
                 getUser·p0.95:   3.551 ms/op
                 getUser·p0.99:   4.035 ms/op
                 getUser·p0.999:  6.467 ms/op
                 getUser·p0.9999: 12.673 ms/op
                 getUser·p1.00:   12.911 ms/op

Iteration   3: 3.001 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.708 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.174 ms/op
                 getUser·p0.999:  6.131 ms/op
                 getUser·p0.9999: 17.596 ms/op
                 getUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320602
  mean =      2.992 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1747 
    [ 1.250,  2.500) = 28254 
    [ 2.500,  3.750) = 276367 
    [ 3.750,  5.000) = 13514 
    [ 5.000,  6.250) = 329 
    [ 6.250,  7.500) = 159 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.216 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.141 ms/op
     p(99.9000) =      6.414 ms/op
     p(99.9900) =     16.923 ms/op
     p(99.9990) =     17.845 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


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
# Warmup Iteration   1: 4.788 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.115 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.918 ±(99.9%) 0.011 ms/op
Iteration   1: 3.870 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.836 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.407 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  13.078 ms/op
                 listUser·p0.9999: 16.429 ms/op
                 listUser·p1.00:   19.268 ms/op

Iteration   2: 3.925 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.283 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.407 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  17.234 ms/op
                 listUser·p0.9999: 24.248 ms/op
                 listUser·p1.00:   24.510 ms/op

Iteration   3: 3.915 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.882 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  17.076 ms/op
                 listUser·p0.9999: 22.505 ms/op
                 listUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246163
  mean =      3.903 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5362 
    [ 2.500,  5.000) = 214058 
    [ 5.000,  7.500) = 25675 
    [ 7.500, 10.000) = 678 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.283 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      5.046 ms/op
     p(95.0000) =      5.431 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     15.420 ms/op
     p(99.9900) =     23.278 ms/op
     p(99.9990) =     24.463 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.473 ± 0.271  ops/ms
ClientGrpc.existUser                       thrpt       3  11.078 ± 1.076  ops/ms
ClientGrpc.getUser                         thrpt       3  10.456 ± 1.934  ops/ms
ClientGrpc.listUser                        thrpt       3   8.012 ± 1.010  ops/ms
ClientGrpc.createUser                       avgt       3   3.098 ± 0.752   ms/op
ClientGrpc.existUser                        avgt       3   2.925 ± 0.503   ms/op
ClientGrpc.getUser                          avgt       3   2.997 ± 0.627   ms/op
ClientGrpc.listUser                         avgt       3   4.057 ± 2.033   ms/op
ClientGrpc.createUser                     sample  306584   3.132 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.690           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.105           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.797           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.944           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.260           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.971           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.130           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.069           ms/op
ClientGrpc.existUser                      sample  331855   2.892 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.417           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.892           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.518           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.736           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.317           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.932           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.195           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.711           ms/op
ClientGrpc.getUser                        sample  320602   2.992 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.216           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.994           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.506           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.715           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.141           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.414           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.923           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.924           ms/op
ClientGrpc.listUser                       sample  246163   3.903 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.283           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.719           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.046           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.431           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.734           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.420           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.278           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.510           ms/op
