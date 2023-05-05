# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.249 ops/ms
# Warmup Iteration   2: 9.180 ops/ms
# Warmup Iteration   3: 10.100 ops/ms
Iteration   1: 10.628 ops/ms
Iteration   2: 10.956 ops/ms
Iteration   3: 10.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.761 ±(99.9%) 3.150 ops/ms [Average]
  (min, avg, max) = (10.628, 10.761, 10.956), stdev = 0.173
  CI (99.9%): [7.611, 13.911] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.117 ops/ms
# Warmup Iteration   2: 10.570 ops/ms
# Warmup Iteration   3: 10.981 ops/ms
Iteration   1: 10.852 ops/ms
Iteration   2: 10.879 ops/ms
Iteration   3: 10.731 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.821 ±(99.9%) 1.434 ops/ms [Average]
  (min, avg, max) = (10.731, 10.821, 10.879), stdev = 0.079
  CI (99.9%): [9.387, 12.254] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.625 ops/ms
# Warmup Iteration   2: 10.193 ops/ms
# Warmup Iteration   3: 10.513 ops/ms
Iteration   1: 10.366 ops/ms
Iteration   2: 10.506 ops/ms
Iteration   3: 10.556 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.476 ±(99.9%) 1.793 ops/ms [Average]
  (min, avg, max) = (10.366, 10.476, 10.556), stdev = 0.098
  CI (99.9%): [8.683, 12.269] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.868 ops/ms
# Warmup Iteration   2: 7.693 ops/ms
# Warmup Iteration   3: 7.930 ops/ms
Iteration   1: 7.932 ops/ms
Iteration   2: 8.136 ops/ms
Iteration   3: 8.042 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.037 ±(99.9%) 1.868 ops/ms [Average]
  (min, avg, max) = (7.932, 8.037, 8.136), stdev = 0.102
  CI (99.9%): [6.169, 9.904] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.305 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.254 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.114 ±(99.9%) 0.002 ms/op
Iteration   1: 3.071 ±(99.9%) 0.003 ms/op
Iteration   2: 3.046 ±(99.9%) 0.004 ms/op
Iteration   3: 3.059 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.059 ±(99.9%) 0.227 ms/op [Average]
  (min, avg, max) = (3.046, 3.059, 3.071), stdev = 0.012
  CI (99.9%): [2.832, 3.285] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.972 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.809 ±(99.9%) 0.003 ms/op
Iteration   1: 2.989 ±(99.9%) 0.003 ms/op
Iteration   2: 2.931 ±(99.9%) 0.002 ms/op
Iteration   3: 2.942 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.954 ±(99.9%) 0.553 ms/op [Average]
  (min, avg, max) = (2.931, 2.954, 2.989), stdev = 0.030
  CI (99.9%): [2.401, 3.507] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.404 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.151 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.002 ms/op
Iteration   1: 3.066 ±(99.9%) 0.003 ms/op
Iteration   2: 3.019 ±(99.9%) 0.003 ms/op
Iteration   3: 3.021 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.035 ±(99.9%) 0.488 ms/op [Average]
  (min, avg, max) = (3.019, 3.035, 3.066), stdev = 0.027
  CI (99.9%): [2.547, 3.523] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.881 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.206 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.035 ±(99.9%) 0.032 ms/op
Iteration   1: 3.905 ±(99.9%) 0.017 ms/op
Iteration   2: 3.959 ±(99.9%) 0.014 ms/op
Iteration   3: 3.942 ±(99.9%) 0.042 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.935 ±(99.9%) 0.504 ms/op [Average]
  (min, avg, max) = (3.905, 3.935, 3.959), stdev = 0.028
  CI (99.9%): [3.431, 4.440] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.400 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.180 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.128 ±(99.9%) 0.006 ms/op
Iteration   1: 3.029 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.909 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  7.694 ms/op
                 createUser·p0.9999: 22.854 ms/op
                 createUser·p1.00:   23.593 ms/op

Iteration   2: 3.030 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.763 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.432 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  6.319 ms/op
                 createUser·p0.9999: 18.800 ms/op
                 createUser·p1.00:   20.546 ms/op

Iteration   3: 3.045 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.698 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   4.568 ms/op
                 createUser·p0.999:  8.233 ms/op
                 createUser·p0.9999: 20.430 ms/op
                 createUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316373
  mean =      3.035 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20995 
    [ 2.500,  5.000) = 293931 
    [ 5.000,  7.500) = 1148 
    [ 7.500, 10.000) = 66 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.698 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      7.312 ms/op
     p(99.9900) =     22.175 ms/op
     p(99.9990) =     23.457 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.076 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.999 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.878 ±(99.9%) 0.006 ms/op
Iteration   1: 2.916 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.777 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   3.998 ms/op
                 existUser·p0.999:  7.134 ms/op
                 existUser·p0.9999: 18.711 ms/op
                 existUser·p1.00:   18.973 ms/op

Iteration   2: 2.887 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.745 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.174 ms/op
                 existUser·p0.999:  6.547 ms/op
                 existUser·p0.9999: 21.949 ms/op
                 existUser·p1.00:   22.577 ms/op

Iteration   3: 2.857 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.833 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.211 ms/op
                 existUser·p0.95:   3.330 ms/op
                 existUser·p0.99:   4.129 ms/op
                 existUser·p0.999:  9.422 ms/op
                 existUser·p0.9999: 16.545 ms/op
                 existUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332567
  mean =      2.886 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42226 
    [ 2.500,  5.000) = 289304 
    [ 5.000,  7.500) = 742 
    [ 7.500, 10.000) = 91 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.745 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.351 ms/op
     p(95.0000) =      3.539 ms/op
     p(99.0000) =      4.104 ms/op
     p(99.9000) =      6.962 ms/op
     p(99.9900) =     18.956 ms/op
     p(99.9990) =     22.490 ms/op
     p(99.9999) =     22.577 ms/op
    p(100.0000) =     22.577 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.129 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.188 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.006 ms/op
Iteration   1: 2.999 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.689 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  6.516 ms/op
                 getUser·p0.9999: 19.464 ms/op
                 getUser·p1.00:   21.234 ms/op

Iteration   2: 3.046 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.542 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.579 ms/op
                 getUser·p0.999:  6.610 ms/op
                 getUser·p0.9999: 17.924 ms/op
                 getUser·p1.00:   18.416 ms/op

Iteration   3: 2.989 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.584 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.432 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  8.012 ms/op
                 getUser·p0.9999: 29.993 ms/op
                 getUser·p1.00:   30.474 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318884
  mean =      3.011 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23373 
    [ 2.500,  5.000) = 293843 
    [ 5.000,  7.500) = 1420 
    [ 7.500, 10.000) = 86 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.542 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      6.759 ms/op
     p(99.9900) =     28.180 ms/op
     p(99.9990) =     30.364 ms/op
     p(99.9999) =     30.474 ms/op
    p(100.0000) =     30.474 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.278 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.110 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.966 ±(99.9%) 0.011 ms/op
Iteration   1: 4.031 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.411 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  14.459 ms/op
                 listUser·p0.9999: 16.782 ms/op
                 listUser·p1.00:   23.560 ms/op

Iteration   2: 3.976 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.984 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   5.308 ms/op
                 listUser·p0.99:   6.755 ms/op
                 listUser·p0.999:  15.387 ms/op
                 listUser·p0.9999: 22.804 ms/op
                 listUser·p1.00:   23.593 ms/op

Iteration   3: 4.003 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.176 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  15.616 ms/op
                 listUser·p0.9999: 18.744 ms/op
                 listUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239808
  mean =      4.003 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1625 
    [ 2.500,  5.000) = 216564 
    [ 5.000,  7.500) = 20346 
    [ 7.500, 10.000) = 822 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 147 
    [15.000, 17.500) = 147 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.984 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.899 ms/op
     p(95.0000) =      5.628 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     14.991 ms/op
     p(99.9900) =     22.381 ms/op
     p(99.9990) =     23.534 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.761 ± 3.150  ops/ms
ClientGrpc.existUser                       thrpt       3  10.821 ± 1.434  ops/ms
ClientGrpc.getUser                         thrpt       3  10.476 ± 1.793  ops/ms
ClientGrpc.listUser                        thrpt       3   8.037 ± 1.868  ops/ms
ClientGrpc.createUser                       avgt       3   3.059 ± 0.227   ms/op
ClientGrpc.existUser                        avgt       3   2.954 ± 0.553   ms/op
ClientGrpc.getUser                          avgt       3   3.035 ± 0.488   ms/op
ClientGrpc.listUser                         avgt       3   3.935 ± 0.504   ms/op
ClientGrpc.createUser                     sample  316373   3.035 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.698           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.006           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.518           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.777           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.489           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.312           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.175           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.593           ms/op
ClientGrpc.existUser                      sample  332567   2.886 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.745           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.351           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.539           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.104           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.962           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.956           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.577           ms/op
ClientGrpc.getUser                        sample  318884   3.011 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.542           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.990           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.502           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.785           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.514           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.759           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.180           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.474           ms/op
ClientGrpc.listUser                       sample  239808   4.003 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.984           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.850           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.899           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.628           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.914           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.991           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.381           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.593           ms/op
