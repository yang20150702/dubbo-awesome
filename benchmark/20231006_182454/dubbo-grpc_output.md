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
# Warmup Iteration   1: 2.637 ops/ms
# Warmup Iteration   2: 6.118 ops/ms
# Warmup Iteration   3: 7.347 ops/ms
Iteration   1: 7.633 ops/ms
Iteration   2: 7.900 ops/ms
Iteration   3: 7.783 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.772 ±(99.9%) 2.440 ops/ms [Average]
  (min, avg, max) = (7.633, 7.772, 7.900), stdev = 0.134
  CI (99.9%): [5.333, 10.212] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.999 ops/ms
# Warmup Iteration   2: 7.648 ops/ms
# Warmup Iteration   3: 8.323 ops/ms
Iteration   1: 8.546 ops/ms
Iteration   2: 8.604 ops/ms
Iteration   3: 8.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.625 ±(99.9%) 1.671 ops/ms [Average]
  (min, avg, max) = (8.546, 8.625, 8.726), stdev = 0.092
  CI (99.9%): [6.955, 10.296] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.256 ops/ms
# Warmup Iteration   2: 7.370 ops/ms
# Warmup Iteration   3: 7.603 ops/ms
Iteration   1: 7.892 ops/ms
Iteration   2: 7.700 ops/ms
Iteration   3: 7.710 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.767 ±(99.9%) 1.964 ops/ms [Average]
  (min, avg, max) = (7.700, 7.767, 7.892), stdev = 0.108
  CI (99.9%): [5.803, 9.732] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.926 ops/ms
# Warmup Iteration   2: 5.585 ops/ms
# Warmup Iteration   3: 6.186 ops/ms
Iteration   1: 6.183 ops/ms
Iteration   2: 6.335 ops/ms
Iteration   3: 6.218 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.245 ±(99.9%) 1.454 ops/ms [Average]
  (min, avg, max) = (6.183, 6.245, 6.335), stdev = 0.080
  CI (99.9%): [4.791, 7.699] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.881 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.429 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.246 ±(99.9%) 0.042 ms/op
Iteration   1: 4.144 ±(99.9%) 0.004 ms/op
Iteration   2: 4.160 ±(99.9%) 0.004 ms/op
Iteration   3: 4.003 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.102 ±(99.9%) 1.581 ms/op [Average]
  (min, avg, max) = (4.003, 4.102, 4.160), stdev = 0.087
  CI (99.9%): [2.521, 5.684] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 5.600 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.027 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.709 ±(99.9%) 0.007 ms/op
Iteration   1: 3.685 ±(99.9%) 0.004 ms/op
Iteration   2: 3.682 ±(99.9%) 0.006 ms/op
Iteration   3: 3.698 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.688 ±(99.9%) 0.155 ms/op [Average]
  (min, avg, max) = (3.682, 3.688, 3.698), stdev = 0.009
  CI (99.9%): [3.533, 3.844] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 5.597 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.146 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.009 ±(99.9%) 0.005 ms/op
Iteration   1: 4.068 ±(99.9%) 0.004 ms/op
Iteration   2: 3.946 ±(99.9%) 0.004 ms/op
Iteration   3: 4.004 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.006 ±(99.9%) 1.111 ms/op [Average]
  (min, avg, max) = (3.946, 4.006, 4.068), stdev = 0.061
  CI (99.9%): [2.895, 5.117] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 6.769 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 5.709 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 5.067 ±(99.9%) 0.019 ms/op
Iteration   1: 4.979 ±(99.9%) 0.014 ms/op
Iteration   2: 4.854 ±(99.9%) 0.009 ms/op
Iteration   3: 4.960 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.931 ±(99.9%) 1.229 ms/op [Average]
  (min, avg, max) = (4.854, 4.931, 4.979), stdev = 0.067
  CI (99.9%): [3.702, 6.160] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 5.697 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.292 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.086 ±(99.9%) 0.011 ms/op
Iteration   1: 4.023 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.864 ms/op
                 createUser·p0.50:   3.912 ms/op
                 createUser·p0.90:   4.858 ms/op
                 createUser·p0.95:   5.317 ms/op
                 createUser·p0.99:   7.660 ms/op
                 createUser·p0.999:  12.606 ms/op
                 createUser·p0.9999: 17.042 ms/op
                 createUser·p1.00:   17.465 ms/op

Iteration   2: 3.977 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.118 ms/op
                 createUser·p0.50:   3.867 ms/op
                 createUser·p0.90:   4.891 ms/op
                 createUser·p0.95:   5.341 ms/op
                 createUser·p0.99:   6.996 ms/op
                 createUser·p0.999:  13.127 ms/op
                 createUser·p0.9999: 15.905 ms/op
                 createUser·p1.00:   19.300 ms/op

Iteration   3: 4.131 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.988 ms/op
                 createUser·p0.50:   3.994 ms/op
                 createUser·p0.90:   5.112 ms/op
                 createUser·p0.95:   5.587 ms/op
                 createUser·p0.99:   7.348 ms/op
                 createUser·p0.999:  17.023 ms/op
                 createUser·p0.9999: 20.333 ms/op
                 createUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 237484
  mean =      4.043 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5448 
    [ 2.500,  5.000) = 209968 
    [ 5.000,  7.500) = 19980 
    [ 7.500, 10.000) = 1521 
    [10.000, 12.500) = 250 
    [12.500, 15.000) = 162 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      3.920 ms/op
     p(90.0000) =      4.956 ms/op
     p(95.0000) =      5.431 ms/op
     p(99.0000) =      7.307 ms/op
     p(99.9000) =     13.730 ms/op
     p(99.9900) =     19.309 ms/op
     p(99.9990) =     20.926 ms/op
     p(99.9999) =     21.627 ms/op
    p(100.0000) =     21.627 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.464 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.078 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.880 ±(99.9%) 0.010 ms/op
Iteration   1: 3.783 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.049 ms/op
                 existUser·p0.50:   3.690 ms/op
                 existUser·p0.90:   4.497 ms/op
                 existUser·p0.95:   4.874 ms/op
                 existUser·p0.99:   6.671 ms/op
                 existUser·p0.999:  10.076 ms/op
                 existUser·p0.9999: 14.403 ms/op
                 existUser·p1.00:   20.185 ms/op

Iteration   2: 3.725 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.981 ms/op
                 existUser·p0.50:   3.625 ms/op
                 existUser·p0.90:   4.375 ms/op
                 existUser·p0.95:   4.792 ms/op
                 existUser·p0.99:   6.504 ms/op
                 existUser·p0.999:  14.992 ms/op
                 existUser·p0.9999: 29.518 ms/op
                 existUser·p1.00:   29.950 ms/op

Iteration   3: 3.746 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.489 ms/op
                 existUser·p0.50:   3.670 ms/op
                 existUser·p0.90:   4.530 ms/op
                 existUser·p0.95:   4.973 ms/op
                 existUser·p0.99:   6.611 ms/op
                 existUser·p0.999:  10.762 ms/op
                 existUser·p0.9999: 19.348 ms/op
                 existUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 256021
  mean =      3.751 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6010 
    [ 2.500,  5.000) = 239207 
    [ 5.000,  7.500) = 9428 
    [ 7.500, 10.000) = 1014 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.489 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      6.595 ms/op
     p(99.9000) =     11.255 ms/op
     p(99.9900) =     28.600 ms/op
     p(99.9990) =     29.899 ms/op
     p(99.9999) =     29.950 ms/op
    p(100.0000) =     29.950 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.985 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.178 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.002 ±(99.9%) 0.011 ms/op
Iteration   1: 3.993 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.941 ms/op
                 getUser·p0.50:   3.858 ms/op
                 getUser·p0.90:   4.932 ms/op
                 getUser·p0.95:   5.439 ms/op
                 getUser·p0.99:   7.406 ms/op
                 getUser·p0.999:  12.500 ms/op
                 getUser·p0.9999: 27.885 ms/op
                 getUser·p1.00:   29.164 ms/op

Iteration   2: 3.965 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.910 ms/op
                 getUser·p0.50:   3.813 ms/op
                 getUser·p0.90:   4.841 ms/op
                 getUser·p0.95:   5.579 ms/op
                 getUser·p0.99:   8.684 ms/op
                 getUser·p0.999:  15.005 ms/op
                 getUser·p0.9999: 25.885 ms/op
                 getUser·p1.00:   26.411 ms/op

Iteration   3: 3.977 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.912 ms/op
                 getUser·p0.50:   3.854 ms/op
                 getUser·p0.90:   4.932 ms/op
                 getUser·p0.95:   5.472 ms/op
                 getUser·p0.99:   8.216 ms/op
                 getUser·p0.999:  14.122 ms/op
                 getUser·p0.9999: 23.231 ms/op
                 getUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 241117
  mean =      3.978 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10249 
    [ 2.500,  5.000) = 209573 
    [ 5.000,  7.500) = 17976 
    [ 7.500, 10.000) = 2407 
    [10.000, 12.500) = 502 
    [12.500, 15.000) = 230 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      0.910 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.907 ms/op
     p(95.0000) =      5.489 ms/op
     p(99.0000) =      8.264 ms/op
     p(99.9000) =     13.892 ms/op
     p(99.9900) =     25.985 ms/op
     p(99.9990) =     28.630 ms/op
     p(99.9999) =     29.164 ms/op
    p(100.0000) =     29.164 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 7.536 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 5.625 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.078 ±(99.9%) 0.021 ms/op
Iteration   1: 5.198 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.597 ms/op
                 listUser·p0.50:   4.809 ms/op
                 listUser·p0.90:   7.176 ms/op
                 listUser·p0.95:   8.102 ms/op
                 listUser·p0.99:   10.256 ms/op
                 listUser·p0.999:  16.876 ms/op
                 listUser·p0.9999: 25.423 ms/op
                 listUser·p1.00:   26.804 ms/op

Iteration   2: 5.222 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.382 ms/op
                 listUser·p0.50:   4.809 ms/op
                 listUser·p0.90:   7.242 ms/op
                 listUser·p0.95:   8.225 ms/op
                 listUser·p0.99:   10.626 ms/op
                 listUser·p0.999:  22.926 ms/op
                 listUser·p0.9999: 30.998 ms/op
                 listUser·p1.00:   31.425 ms/op

Iteration   3: 5.039 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.208 ms/op
                 listUser·p0.50:   4.678 ms/op
                 listUser·p0.90:   6.685 ms/op
                 listUser·p0.95:   7.537 ms/op
                 listUser·p0.99:   10.207 ms/op
                 listUser·p0.999:  20.152 ms/op
                 listUser·p0.9999: 32.200 ms/op
                 listUser·p1.00:   32.440 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 186354
  mean =      5.152 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 535 
    [ 2.500,  5.000) = 111238 
    [ 5.000,  7.500) = 61251 
    [ 7.500, 10.000) = 11028 
    [10.000, 12.500) = 1559 
    [12.500, 15.000) = 285 
    [15.000, 17.500) = 180 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.208 ms/op
     p(50.0000) =      4.751 ms/op
     p(90.0000) =      7.045 ms/op
     p(95.0000) =      7.987 ms/op
     p(99.0000) =     10.387 ms/op
     p(99.9000) =     19.638 ms/op
     p(99.9900) =     30.573 ms/op
     p(99.9990) =     32.412 ms/op
     p(99.9999) =     32.440 ms/op
    p(100.0000) =     32.440 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.772 ± 2.440  ops/ms
ClientGrpc.existUser                       thrpt       3   8.625 ± 1.671  ops/ms
ClientGrpc.getUser                         thrpt       3   7.767 ± 1.964  ops/ms
ClientGrpc.listUser                        thrpt       3   6.245 ± 1.454  ops/ms
ClientGrpc.createUser                       avgt       3   4.102 ± 1.581   ms/op
ClientGrpc.existUser                        avgt       3   3.688 ± 0.155   ms/op
ClientGrpc.getUser                          avgt       3   4.006 ± 1.111   ms/op
ClientGrpc.listUser                         avgt       3   4.931 ± 1.229   ms/op
ClientGrpc.createUser                     sample  237484   4.043 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.864           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.920           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.956           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.431           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.307           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.730           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.309           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.627           ms/op
ClientGrpc.existUser                      sample  256021   3.751 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.489           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.662           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.473           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.882           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.595           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.255           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          28.600           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.950           ms/op
ClientGrpc.getUser                        sample  241117   3.978 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.910           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.842           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.907           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.489           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.264           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.892           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.985           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.164           ms/op
ClientGrpc.listUser                       sample  186354   5.152 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.208           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.751           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.045           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.987           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.387           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.638           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.573           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.440           ms/op
