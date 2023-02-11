# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.385 ops/ms
# Warmup Iteration   2: 9.136 ops/ms
# Warmup Iteration   3: 10.151 ops/ms
Iteration   1: 10.459 ops/ms
Iteration   2: 10.176 ops/ms
Iteration   3: 10.251 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.296 ±(99.9%) 2.677 ops/ms [Average]
  (min, avg, max) = (10.176, 10.296, 10.459), stdev = 0.147
  CI (99.9%): [7.619, 12.972] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.178 ops/ms
# Warmup Iteration   2: 10.889 ops/ms
# Warmup Iteration   3: 10.892 ops/ms
Iteration   1: 10.949 ops/ms
Iteration   2: 10.629 ops/ms
Iteration   3: 10.796 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.791 ±(99.9%) 2.917 ops/ms [Average]
  (min, avg, max) = (10.629, 10.791, 10.949), stdev = 0.160
  CI (99.9%): [7.874, 13.709] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 6.804 ops/ms
# Warmup Iteration   2: 10.144 ops/ms
# Warmup Iteration   3: 10.584 ops/ms
Iteration   1: 10.450 ops/ms
Iteration   2: 10.515 ops/ms
Iteration   3: 10.144 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.369 ±(99.9%) 3.612 ops/ms [Average]
  (min, avg, max) = (10.144, 10.369, 10.515), stdev = 0.198
  CI (99.9%): [6.758, 13.981] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.692 ops/ms
# Warmup Iteration   2: 7.730 ops/ms
# Warmup Iteration   3: 7.929 ops/ms
Iteration   1: 8.015 ops/ms
Iteration   2: 8.091 ops/ms
Iteration   3: 8.208 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.105 ±(99.9%) 1.773 ops/ms [Average]
  (min, avg, max) = (8.015, 8.105, 8.208), stdev = 0.097
  CI (99.9%): [6.332, 9.878] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.895 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.128 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.116 ±(99.9%) 0.003 ms/op
Iteration   1: 3.137 ±(99.9%) 0.003 ms/op
Iteration   2: 3.237 ±(99.9%) 0.001 ms/op
Iteration   3: 3.062 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.145 ±(99.9%) 1.602 ms/op [Average]
  (min, avg, max) = (3.062, 3.145, 3.237), stdev = 0.088
  CI (99.9%): [1.544, 4.747] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.535 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.109 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.984 ±(99.9%) 0.003 ms/op
Iteration   1: 2.923 ±(99.9%) 0.002 ms/op
Iteration   2: 3.013 ±(99.9%) 0.002 ms/op
Iteration   3: 2.979 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.972 ±(99.9%) 0.833 ms/op [Average]
  (min, avg, max) = (2.923, 2.972, 3.013), stdev = 0.046
  CI (99.9%): [2.139, 3.805] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.014 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.168 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.129 ±(99.9%) 0.003 ms/op
Iteration   1: 3.076 ±(99.9%) 0.002 ms/op
Iteration   2: 3.074 ±(99.9%) 0.002 ms/op
Iteration   3: 3.060 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.070 ±(99.9%) 0.160 ms/op [Average]
  (min, avg, max) = (3.060, 3.070, 3.076), stdev = 0.009
  CI (99.9%): [2.910, 3.230] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.204 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.115 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.055 ±(99.9%) 0.013 ms/op
Iteration   1: 4.095 ±(99.9%) 0.008 ms/op
Iteration   2: 4.086 ±(99.9%) 0.029 ms/op
Iteration   3: 4.112 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.098 ±(99.9%) 0.244 ms/op [Average]
  (min, avg, max) = (4.086, 4.098, 4.112), stdev = 0.013
  CI (99.9%): [3.854, 4.342] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.994 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.231 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.207 ±(99.9%) 0.007 ms/op
Iteration   1: 3.181 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.702 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.071 ms/op
                 createUser·p0.99:   4.634 ms/op
                 createUser·p0.999:  9.379 ms/op
                 createUser·p0.9999: 18.873 ms/op
                 createUser·p1.00:   19.333 ms/op

Iteration   2: 3.168 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.818 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.883 ms/op
                 createUser·p0.95:   4.084 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  6.929 ms/op
                 createUser·p0.9999: 15.183 ms/op
                 createUser·p1.00:   15.581 ms/op

Iteration   3: 3.215 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.610 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.916 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  8.526 ms/op
                 createUser·p0.9999: 24.217 ms/op
                 createUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 301192
  mean =      3.188 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22365 
    [ 2.500,  5.000) = 277621 
    [ 5.000,  7.500) = 768 
    [ 7.500, 10.000) = 196 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.610 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      8.864 ms/op
     p(99.9900) =     21.987 ms/op
     p(99.9990) =     24.543 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.949 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.045 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.006 ms/op
Iteration   1: 2.994 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.670 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.686 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   4.141 ms/op
                 existUser·p0.999:  5.744 ms/op
                 existUser·p0.9999: 10.775 ms/op
                 existUser·p1.00:   10.994 ms/op

Iteration   2: 2.957 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.643 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   4.182 ms/op
                 existUser·p0.999:  10.551 ms/op
                 existUser·p0.9999: 19.628 ms/op
                 existUser·p1.00:   20.152 ms/op

Iteration   3: 3.001 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.636 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.580 ms/op
                 existUser·p0.95:   3.768 ms/op
                 existUser·p0.99:   4.174 ms/op
                 existUser·p0.999:  7.356 ms/op
                 existUser·p0.9999: 17.411 ms/op
                 existUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321802
  mean =      2.984 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43599 
    [ 2.500,  5.000) = 277468 
    [ 5.000,  7.500) = 472 
    [ 7.500, 10.000) = 39 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.636 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.166 ms/op
     p(99.9000) =      6.547 ms/op
     p(99.9900) =     18.210 ms/op
     p(99.9990) =     20.040 ms/op
     p(99.9999) =     20.152 ms/op
    p(100.0000) =     20.152 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.564 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.006 ms/op
Iteration   1: 3.071 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.843 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  7.192 ms/op
                 getUser·p0.9999: 13.779 ms/op
                 getUser·p1.00:   15.450 ms/op

Iteration   2: 3.165 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.680 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.867 ms/op
                 getUser·p0.95:   4.047 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  7.301 ms/op
                 getUser·p0.9999: 20.444 ms/op
                 getUser·p1.00:   21.103 ms/op

Iteration   3: 3.133 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.687 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  7.464 ms/op
                 getUser·p0.9999: 19.497 ms/op
                 getUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307226
  mean =      3.122 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21693 
    [ 2.500,  5.000) = 284472 
    [ 5.000,  7.500) = 767 
    [ 7.500, 10.000) = 51 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      7.332 ms/op
     p(99.9900) =     19.754 ms/op
     p(99.9990) =     20.801 ms/op
     p(99.9999) =     21.103 ms/op
    p(100.0000) =     21.103 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.651 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.155 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.009 ±(99.9%) 0.012 ms/op
Iteration   1: 3.914 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.868 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  12.554 ms/op
                 listUser·p0.9999: 16.061 ms/op
                 listUser·p1.00:   18.285 ms/op

Iteration   2: 3.985 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.266 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  14.548 ms/op
                 listUser·p0.9999: 17.268 ms/op
                 listUser·p1.00:   20.185 ms/op

Iteration   3: 3.930 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.824 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.496 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  14.483 ms/op
                 listUser·p0.9999: 21.163 ms/op
                 listUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243562
  mean =      3.943 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4772 
    [ 2.500,  5.000) = 212447 
    [ 5.000,  7.500) = 25077 
    [ 7.500, 10.000) = 844 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 190 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      5.071 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      6.835 ms/op
     p(99.9000) =     14.212 ms/op
     p(99.9900) =     20.775 ms/op
     p(99.9990) =     21.252 ms/op
     p(99.9999) =     22.544 ms/op
    p(100.0000) =     22.544 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.296 ± 2.677  ops/ms
ClientGrpc.existUser                       thrpt       3  10.791 ± 2.917  ops/ms
ClientGrpc.getUser                         thrpt       3  10.369 ± 3.612  ops/ms
ClientGrpc.listUser                        thrpt       3   8.105 ± 1.773  ops/ms
ClientGrpc.createUser                       avgt       3   3.145 ± 1.602   ms/op
ClientGrpc.existUser                        avgt       3   2.972 ± 0.833   ms/op
ClientGrpc.getUser                          avgt       3   3.070 ± 0.160   ms/op
ClientGrpc.listUser                         avgt       3   4.098 ± 0.244   ms/op
ClientGrpc.createUser                     sample  301192   3.188 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.610           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.170           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.887           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.080           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.473           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.864           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.987           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.707           ms/op
ClientGrpc.existUser                      sample  321802   2.984 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.636           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.982           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.621           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.805           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.166           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.547           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.210           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.152           ms/op
ClientGrpc.getUser                        sample  307226   3.122 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.680           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.105           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.748           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.973           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.424           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.332           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.754           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.103           ms/op
ClientGrpc.listUser                       sample  243562   3.943 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.824           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.785           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.071           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.669           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.835           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.212           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.775           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.544           ms/op
