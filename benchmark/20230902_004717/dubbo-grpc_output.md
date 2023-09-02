# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.495 ops/ms
# Warmup Iteration   2: 9.251 ops/ms
# Warmup Iteration   3: 10.231 ops/ms
Iteration   1: 10.403 ops/ms
Iteration   2: 10.717 ops/ms
Iteration   3: 10.567 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.562 ±(99.9%) 2.865 ops/ms [Average]
  (min, avg, max) = (10.403, 10.562, 10.717), stdev = 0.157
  CI (99.9%): [7.697, 13.428] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.824 ops/ms
# Warmup Iteration   2: 10.844 ops/ms
# Warmup Iteration   3: 10.899 ops/ms
Iteration   1: 11.148 ops/ms
Iteration   2: 11.355 ops/ms
Iteration   3: 11.140 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.214 ±(99.9%) 2.222 ops/ms [Average]
  (min, avg, max) = (11.140, 11.214, 11.355), stdev = 0.122
  CI (99.9%): [8.993, 13.436] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.194 ops/ms
# Warmup Iteration   2: 10.322 ops/ms
# Warmup Iteration   3: 10.632 ops/ms
Iteration   1: 10.890 ops/ms
Iteration   2: 10.808 ops/ms
Iteration   3: 10.620 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.772 ±(99.9%) 2.526 ops/ms [Average]
  (min, avg, max) = (10.620, 10.772, 10.890), stdev = 0.138
  CI (99.9%): [8.247, 13.298] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.272 ops/ms
# Warmup Iteration   2: 7.704 ops/ms
# Warmup Iteration   3: 8.169 ops/ms
Iteration   1: 8.069 ops/ms
Iteration   2: 8.217 ops/ms
Iteration   3: 8.173 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.153 ±(99.9%) 1.382 ops/ms [Average]
  (min, avg, max) = (8.069, 8.153, 8.217), stdev = 0.076
  CI (99.9%): [6.771, 9.536] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.091 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.165 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.003 ms/op
Iteration   1: 3.008 ±(99.9%) 0.003 ms/op
Iteration   2: 2.958 ±(99.9%) 0.002 ms/op
Iteration   3: 2.991 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.986 ±(99.9%) 0.467 ms/op [Average]
  (min, avg, max) = (2.958, 2.986, 3.008), stdev = 0.026
  CI (99.9%): [2.518, 3.453] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.964 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.963 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.861 ±(99.9%) 0.003 ms/op
Iteration   1: 2.846 ±(99.9%) 0.003 ms/op
Iteration   2: 2.892 ±(99.9%) 0.004 ms/op
Iteration   3: 2.804 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.847 ±(99.9%) 0.803 ms/op [Average]
  (min, avg, max) = (2.804, 2.847, 2.892), stdev = 0.044
  CI (99.9%): [2.045, 3.650] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.092 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.040 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.963 ±(99.9%) 0.003 ms/op
Iteration   1: 3.031 ±(99.9%) 0.006 ms/op
Iteration   2: 2.979 ±(99.9%) 0.003 ms/op
Iteration   3: 3.012 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.007 ±(99.9%) 0.481 ms/op [Average]
  (min, avg, max) = (2.979, 3.007, 3.031), stdev = 0.026
  CI (99.9%): [2.526, 3.488] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.107 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.853 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.926 ±(99.9%) 0.008 ms/op
Iteration   1: 3.983 ±(99.9%) 0.037 ms/op
Iteration   2: 3.954 ±(99.9%) 0.018 ms/op
Iteration   3: 3.876 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.938 ±(99.9%) 1.011 ms/op [Average]
  (min, avg, max) = (3.876, 3.938, 3.983), stdev = 0.055
  CI (99.9%): [2.927, 4.949] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.091 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.168 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.072 ±(99.9%) 0.007 ms/op
Iteration   1: 3.023 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.856 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  8.094 ms/op
                 createUser·p0.9999: 22.656 ms/op
                 createUser·p1.00:   23.101 ms/op

Iteration   2: 2.989 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.682 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  8.553 ms/op
                 createUser·p0.9999: 14.880 ms/op
                 createUser·p1.00:   15.516 ms/op

Iteration   3: 3.064 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.889 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  8.999 ms/op
                 createUser·p0.9999: 14.141 ms/op
                 createUser·p1.00:   14.516 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317317
  mean =      3.025 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26197 
    [ 2.500,  5.000) = 289279 
    [ 5.000,  7.500) = 1336 
    [ 7.500, 10.000) = 277 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.682 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      8.471 ms/op
     p(99.9900) =     21.791 ms/op
     p(99.9990) =     22.992 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.587 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.974 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.864 ±(99.9%) 0.006 ms/op
Iteration   1: 2.890 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.556 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  6.811 ms/op
                 existUser·p0.9999: 12.101 ms/op
                 existUser·p1.00:   13.550 ms/op

Iteration   2: 2.905 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.690 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.645 ms/op
                 existUser·p0.999:  8.317 ms/op
                 existUser·p0.9999: 22.578 ms/op
                 existUser·p1.00:   24.019 ms/op

Iteration   3: 2.923 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.522 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   4.571 ms/op
                 existUser·p0.999:  7.127 ms/op
                 existUser·p0.9999: 15.663 ms/op
                 existUser·p1.00:   16.007 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330167
  mean =      2.906 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50239 
    [ 2.500,  5.000) = 278275 
    [ 5.000,  7.500) = 1304 
    [ 7.500, 10.000) = 188 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.522 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      7.619 ms/op
     p(99.9900) =     16.186 ms/op
     p(99.9990) =     23.026 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.124 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.104 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.006 ms/op
Iteration   1: 2.959 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.569 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   4.407 ms/op
                 getUser·p0.999:  7.274 ms/op
                 getUser·p0.9999: 12.445 ms/op
                 getUser·p1.00:   12.763 ms/op

Iteration   2: 2.991 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.408 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   4.669 ms/op
                 getUser·p0.999:  11.486 ms/op
                 getUser·p0.9999: 13.828 ms/op
                 getUser·p1.00:   14.008 ms/op

Iteration   3: 3.006 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.641 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.440 ms/op
                 getUser·p0.95:   3.645 ms/op
                 getUser·p0.99:   4.153 ms/op
                 getUser·p0.999:  7.219 ms/op
                 getUser·p0.9999: 25.636 ms/op
                 getUser·p1.00:   25.887 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321354
  mean =      2.986 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26285 
    [ 2.500,  5.000) = 293233 
    [ 5.000,  7.500) = 1423 
    [ 7.500, 10.000) = 153 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.408 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      8.126 ms/op
     p(99.9900) =     23.864 ms/op
     p(99.9990) =     25.814 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.367 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.095 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.948 ±(99.9%) 0.011 ms/op
Iteration   1: 3.898 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.397 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  12.583 ms/op
                 listUser·p0.9999: 22.392 ms/op
                 listUser·p1.00:   22.708 ms/op

Iteration   2: 3.895 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.946 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  14.270 ms/op
                 listUser·p0.9999: 20.178 ms/op
                 listUser·p1.00:   20.611 ms/op

Iteration   3: 3.964 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.728 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  13.521 ms/op
                 listUser·p0.9999: 22.118 ms/op
                 listUser·p1.00:   22.807 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245044
  mean =      3.919 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5279 
    [ 2.500,  5.000) = 217315 
    [ 5.000,  7.500) = 20965 
    [ 7.500, 10.000) = 1011 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 196 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.728 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.915 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     13.614 ms/op
     p(99.9900) =     22.102 ms/op
     p(99.9990) =     22.693 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.562 ± 2.865  ops/ms
ClientGrpc.existUser                       thrpt       3  11.214 ± 2.222  ops/ms
ClientGrpc.getUser                         thrpt       3  10.772 ± 2.526  ops/ms
ClientGrpc.listUser                        thrpt       3   8.153 ± 1.382  ops/ms
ClientGrpc.createUser                       avgt       3   2.986 ± 0.467   ms/op
ClientGrpc.existUser                        avgt       3   2.847 ± 0.803   ms/op
ClientGrpc.getUser                          avgt       3   3.007 ± 0.481   ms/op
ClientGrpc.listUser                         avgt       3   3.938 ± 1.011   ms/op
ClientGrpc.createUser                     sample  317317   3.025 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.682           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.002           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.547           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.744           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.497           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.471           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.791           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.101           ms/op
ClientGrpc.existUser                      sample  330167   2.906 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.522           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.432           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.670           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.522           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.619           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.186           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.019           ms/op
ClientGrpc.getUser                        sample  321354   2.986 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.408           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.974           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.457           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.678           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.126           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.864           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.887           ms/op
ClientGrpc.listUser                       sample  245044   3.919 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.728           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.777           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.915           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.693           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.906           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.614           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.102           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.807           ms/op
