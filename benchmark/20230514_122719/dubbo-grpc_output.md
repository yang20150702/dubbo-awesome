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
# Warmup Iteration   1: 2.859 ops/ms
# Warmup Iteration   2: 5.999 ops/ms
# Warmup Iteration   3: 6.991 ops/ms
Iteration   1: 8.129 ops/ms
Iteration   2: 8.699 ops/ms
Iteration   3: 8.526 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.451 ±(99.9%) 5.337 ops/ms [Average]
  (min, avg, max) = (8.129, 8.451, 8.699), stdev = 0.293
  CI (99.9%): [3.114, 13.789] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.796 ops/ms
# Warmup Iteration   2: 8.075 ops/ms
# Warmup Iteration   3: 8.921 ops/ms
Iteration   1: 8.595 ops/ms
Iteration   2: 9.134 ops/ms
Iteration   3: 8.968 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.899 ±(99.9%) 5.042 ops/ms [Average]
  (min, avg, max) = (8.595, 8.899, 9.134), stdev = 0.276
  CI (99.9%): [3.857, 13.941] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 5.799 ops/ms
# Warmup Iteration   2: 8.169 ops/ms
# Warmup Iteration   3: 8.190 ops/ms
Iteration   1: 8.384 ops/ms
Iteration   2: 8.697 ops/ms
Iteration   3: 8.767 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.616 ±(99.9%) 3.715 ops/ms [Average]
  (min, avg, max) = (8.384, 8.616, 8.767), stdev = 0.204
  CI (99.9%): [4.901, 12.331] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.103 ops/ms
# Warmup Iteration   2: 6.182 ops/ms
# Warmup Iteration   3: 6.496 ops/ms
Iteration   1: 6.572 ops/ms
Iteration   2: 6.719 ops/ms
Iteration   3: 6.761 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.684 ±(99.9%) 1.817 ops/ms [Average]
  (min, avg, max) = (6.572, 6.684, 6.761), stdev = 0.100
  CI (99.9%): [4.867, 8.501] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.671 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.943 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.844 ±(99.9%) 0.029 ms/op
Iteration   1: 3.626 ±(99.9%) 0.004 ms/op
Iteration   2: 3.648 ±(99.9%) 0.003 ms/op
Iteration   3: 3.716 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.663 ±(99.9%) 0.849 ms/op [Average]
  (min, avg, max) = (3.626, 3.663, 3.716), stdev = 0.047
  CI (99.9%): [2.814, 4.512] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.932 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.800 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.694 ±(99.9%) 0.005 ms/op
Iteration   1: 3.522 ±(99.9%) 0.002 ms/op
Iteration   2: 3.561 ±(99.9%) 0.003 ms/op
Iteration   3: 3.542 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.542 ±(99.9%) 0.350 ms/op [Average]
  (min, avg, max) = (3.522, 3.542, 3.561), stdev = 0.019
  CI (99.9%): [3.192, 3.892] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.202 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.105 ±(99.9%) 0.054 ms/op
# Warmup Iteration   3: 3.805 ±(99.9%) 0.003 ms/op
Iteration   1: 3.900 ±(99.9%) 0.003 ms/op
Iteration   2: 3.744 ±(99.9%) 0.005 ms/op
Iteration   3: 3.704 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.782 ±(99.9%) 1.891 ms/op [Average]
  (min, avg, max) = (3.704, 3.782, 3.900), stdev = 0.104
  CI (99.9%): [1.891, 5.674] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.727 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.920 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.942 ±(99.9%) 0.012 ms/op
Iteration   1: 4.810 ±(99.9%) 0.018 ms/op
Iteration   2: 4.942 ±(99.9%) 0.012 ms/op
Iteration   3: 5.084 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.945 ±(99.9%) 2.498 ms/op [Average]
  (min, avg, max) = (4.810, 4.945, 5.084), stdev = 0.137
  CI (99.9%): [2.447, 7.444] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.342 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.877 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.717 ±(99.9%) 0.011 ms/op
Iteration   1: 3.912 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.169 ms/op
                 createUser·p0.50:   3.756 ms/op
                 createUser·p0.90:   4.743 ms/op
                 createUser·p0.95:   5.243 ms/op
                 createUser·p0.99:   7.258 ms/op
                 createUser·p0.999:  17.244 ms/op
                 createUser·p0.9999: 30.725 ms/op
                 createUser·p1.00:   33.030 ms/op

Iteration   2: 3.738 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.951 ms/op
                 createUser·p0.50:   3.637 ms/op
                 createUser·p0.90:   4.547 ms/op
                 createUser·p0.95:   5.071 ms/op
                 createUser·p0.99:   6.668 ms/op
                 createUser·p0.999:  12.452 ms/op
                 createUser·p0.9999: 30.756 ms/op
                 createUser·p1.00:   31.228 ms/op

Iteration   3: 3.693 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.866 ms/op
                 createUser·p0.50:   3.613 ms/op
                 createUser·p0.90:   4.399 ms/op
                 createUser·p0.95:   4.768 ms/op
                 createUser·p0.99:   6.278 ms/op
                 createUser·p0.999:  10.530 ms/op
                 createUser·p0.9999: 24.663 ms/op
                 createUser·p1.00:   25.264 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 254078
  mean =      3.779 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6308 
    [ 2.500,  5.000) = 234666 
    [ 5.000,  7.500) = 11567 
    [ 7.500, 10.000) = 1055 
    [10.000, 12.500) = 179 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.866 ms/op
     p(50.0000) =      3.666 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      5.022 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     13.173 ms/op
     p(99.9900) =     30.363 ms/op
     p(99.9990) =     32.962 ms/op
     p(99.9999) =     33.030 ms/op
    p(100.0000) =     33.030 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 4.965 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.803 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.553 ±(99.9%) 0.009 ms/op
Iteration   1: 3.651 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.008 ms/op
                 existUser·p0.50:   3.494 ms/op
                 existUser·p0.90:   4.522 ms/op
                 existUser·p0.95:   5.177 ms/op
                 existUser·p0.99:   6.856 ms/op
                 existUser·p0.999:  10.725 ms/op
                 existUser·p0.9999: 18.202 ms/op
                 existUser·p1.00:   19.038 ms/op

Iteration   2: 3.547 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.019 ms/op
                 existUser·p0.50:   3.453 ms/op
                 existUser·p0.90:   4.170 ms/op
                 existUser·p0.95:   4.596 ms/op
                 existUser·p0.99:   6.087 ms/op
                 existUser·p0.999:  13.065 ms/op
                 existUser·p0.9999: 22.215 ms/op
                 existUser·p1.00:   22.512 ms/op

Iteration   3: 3.540 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.828 ms/op
                 existUser·p0.50:   3.473 ms/op
                 existUser·p0.90:   4.366 ms/op
                 existUser·p0.95:   4.776 ms/op
                 existUser·p0.99:   6.193 ms/op
                 existUser·p0.999:  10.129 ms/op
                 existUser·p0.9999: 34.996 ms/op
                 existUser·p1.00:   35.389 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 268275
  mean =      3.578 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10576 
    [ 2.500,  5.000) = 246390 
    [ 5.000,  7.500) = 10080 
    [ 7.500, 10.000) = 882 
    [10.000, 12.500) = 151 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.828 ms/op
     p(50.0000) =      3.473 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      6.414 ms/op
     p(99.9000) =     11.010 ms/op
     p(99.9900) =     34.287 ms/op
     p(99.9990) =     35.345 ms/op
     p(99.9999) =     35.389 ms/op
    p(100.0000) =     35.389 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.361 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.946 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.651 ±(99.9%) 0.007 ms/op
Iteration   1: 3.737 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.114 ms/op
                 getUser·p0.50:   3.658 ms/op
                 getUser·p0.90:   4.506 ms/op
                 getUser·p0.95:   4.866 ms/op
                 getUser·p0.99:   6.103 ms/op
                 getUser·p0.999:  7.946 ms/op
                 getUser·p0.9999: 14.390 ms/op
                 getUser·p1.00:   14.647 ms/op

Iteration   2: 3.672 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.921 ms/op
                 getUser·p0.50:   3.613 ms/op
                 getUser·p0.90:   4.358 ms/op
                 getUser·p0.95:   4.702 ms/op
                 getUser·p0.99:   5.898 ms/op
                 getUser·p0.999:  8.550 ms/op
                 getUser·p0.9999: 19.774 ms/op
                 getUser·p1.00:   20.873 ms/op

Iteration   3: 3.771 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.932 ms/op
                 getUser·p0.50:   3.682 ms/op
                 getUser·p0.90:   4.678 ms/op
                 getUser·p0.95:   5.112 ms/op
                 getUser·p0.99:   6.805 ms/op
                 getUser·p0.999:  10.795 ms/op
                 getUser·p0.9999: 19.890 ms/op
                 getUser·p1.00:   22.643 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 257621
  mean =      3.726 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8158 
    [ 2.500,  5.000) = 238500 
    [ 5.000,  7.500) = 10141 
    [ 7.500, 10.000) = 619 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.921 ms/op
     p(50.0000) =      3.650 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      6.275 ms/op
     p(99.9000) =      9.247 ms/op
     p(99.9900) =     19.530 ms/op
     p(99.9990) =     20.817 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


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
# Warmup Iteration   1: 6.370 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 5.492 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.016 ±(99.9%) 0.017 ms/op
Iteration   1: 4.746 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.647 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   6.382 ms/op
                 listUser·p0.95:   7.170 ms/op
                 listUser·p0.99:   9.208 ms/op
                 listUser·p0.999:  18.106 ms/op
                 listUser·p0.9999: 25.125 ms/op
                 listUser·p1.00:   26.083 ms/op

Iteration   2: 4.857 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.257 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   6.210 ms/op
                 listUser·p0.95:   7.009 ms/op
                 listUser·p0.99:   9.208 ms/op
                 listUser·p0.999:  19.610 ms/op
                 listUser·p0.9999: 30.174 ms/op
                 listUser·p1.00:   33.882 ms/op

Iteration   3: 4.848 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.399 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   6.169 ms/op
                 listUser·p0.95:   7.037 ms/op
                 listUser·p0.99:   9.159 ms/op
                 listUser·p0.999:  22.874 ms/op
                 listUser·p0.9999: 34.549 ms/op
                 listUser·p1.00:   38.666 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 199279
  mean =      4.817 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 456 
    [ 2.500,  5.000) = 142977 
    [ 5.000,  7.500) = 49023 
    [ 7.500, 10.000) = 5634 
    [10.000, 12.500) = 691 
    [12.500, 15.000) = 156 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.257 ms/op
     p(50.0000) =      4.563 ms/op
     p(90.0000) =      6.259 ms/op
     p(95.0000) =      7.078 ms/op
     p(99.0000) =      9.191 ms/op
     p(99.9000) =     20.405 ms/op
     p(99.9900) =     33.327 ms/op
     p(99.9990) =     38.341 ms/op
     p(99.9999) =     38.666 ms/op
    p(100.0000) =     38.666 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.451 ± 5.337  ops/ms
ClientGrpc.existUser                       thrpt       3   8.899 ± 5.042  ops/ms
ClientGrpc.getUser                         thrpt       3   8.616 ± 3.715  ops/ms
ClientGrpc.listUser                        thrpt       3   6.684 ± 1.817  ops/ms
ClientGrpc.createUser                       avgt       3   3.663 ± 0.849   ms/op
ClientGrpc.existUser                        avgt       3   3.542 ± 0.350   ms/op
ClientGrpc.getUser                          avgt       3   3.782 ± 1.891   ms/op
ClientGrpc.listUser                         avgt       3   4.945 ± 2.498   ms/op
ClientGrpc.createUser                     sample  254078   3.779 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.866           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.666           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.571           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.022           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.717           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.173           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          30.363           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.030           ms/op
ClientGrpc.existUser                      sample  268275   3.578 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.828           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.473           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.350           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.850           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.414           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.010           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          34.287           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          35.389           ms/op
ClientGrpc.getUser                        sample  257621   3.726 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.921           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.650           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.514           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.899           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.275           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.247           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.530           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.643           ms/op
ClientGrpc.listUser                       sample  199279   4.817 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.257           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.563           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.259           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.078           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.191           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.405           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          33.327           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          38.666           ms/op
