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
# Warmup Iteration   1: 4.824 ops/ms
# Warmup Iteration   2: 10.025 ops/ms
# Warmup Iteration   3: 11.038 ops/ms
Iteration   1: 10.857 ops/ms
Iteration   2: 10.053 ops/ms
Iteration   3: 10.232 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.381 ±(99.9%) 7.697 ops/ms [Average]
  (min, avg, max) = (10.053, 10.381, 10.857), stdev = 0.422
  CI (99.9%): [2.683, 18.078] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.192 ops/ms
# Warmup Iteration   2: 10.869 ops/ms
# Warmup Iteration   3: 11.474 ops/ms
Iteration   1: 10.951 ops/ms
Iteration   2: 11.286 ops/ms
Iteration   3: 10.965 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.068 ±(99.9%) 3.461 ops/ms [Average]
  (min, avg, max) = (10.951, 11.068, 11.286), stdev = 0.190
  CI (99.9%): [7.606, 14.529] (assumes normal distribution)


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
# Warmup Iteration   1: 7.966 ops/ms
# Warmup Iteration   2: 10.460 ops/ms
# Warmup Iteration   3: 10.447 ops/ms
Iteration   1: 10.708 ops/ms
Iteration   2: 10.677 ops/ms
Iteration   3: 10.535 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.640 ±(99.9%) 1.678 ops/ms [Average]
  (min, avg, max) = (10.535, 10.640, 10.708), stdev = 0.092
  CI (99.9%): [8.962, 12.318] (assumes normal distribution)


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
# Warmup Iteration   1: 5.900 ops/ms
# Warmup Iteration   2: 7.859 ops/ms
# Warmup Iteration   3: 8.190 ops/ms
Iteration   1: 8.146 ops/ms
Iteration   2: 8.269 ops/ms
Iteration   3: 8.143 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.186 ±(99.9%) 1.315 ops/ms [Average]
  (min, avg, max) = (8.143, 8.186, 8.269), stdev = 0.072
  CI (99.9%): [6.871, 9.501] (assumes normal distribution)


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
# Warmup Iteration   1: 3.969 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.002 ms/op
Iteration   1: 3.052 ±(99.9%) 0.003 ms/op
Iteration   2: 3.123 ±(99.9%) 0.001 ms/op
Iteration   3: 3.133 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.102 ±(99.9%) 0.806 ms/op [Average]
  (min, avg, max) = (3.052, 3.102, 3.133), stdev = 0.044
  CI (99.9%): [2.296, 3.909] (assumes normal distribution)


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
# Warmup Iteration   1: 3.734 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.915 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.828 ±(99.9%) 0.002 ms/op
Iteration   1: 2.887 ±(99.9%) 0.003 ms/op
Iteration   2: 2.844 ±(99.9%) 0.003 ms/op
Iteration   3: 2.869 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.867 ±(99.9%) 0.390 ms/op [Average]
  (min, avg, max) = (2.844, 2.867, 2.887), stdev = 0.021
  CI (99.9%): [2.477, 3.256] (assumes normal distribution)


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
# Warmup Iteration   1: 3.957 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.085 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.002 ms/op
Iteration   1: 2.974 ±(99.9%) 0.002 ms/op
Iteration   2: 3.021 ±(99.9%) 0.003 ms/op
Iteration   3: 2.913 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.969 ±(99.9%) 0.988 ms/op [Average]
  (min, avg, max) = (2.913, 2.969, 3.021), stdev = 0.054
  CI (99.9%): [1.981, 3.957] (assumes normal distribution)


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
# Warmup Iteration   1: 4.254 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 4.100 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.974 ±(99.9%) 0.026 ms/op
Iteration   1: 3.926 ±(99.9%) 0.041 ms/op
Iteration   2: 3.973 ±(99.9%) 0.023 ms/op
Iteration   3: 3.966 ±(99.9%) 0.048 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.955 ±(99.9%) 0.463 ms/op [Average]
  (min, avg, max) = (3.926, 3.955, 3.973), stdev = 0.025
  CI (99.9%): [3.492, 4.418] (assumes normal distribution)


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
# Warmup Iteration   1: 4.016 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.006 ms/op
Iteration   1: 3.063 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.721 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  7.812 ms/op
                 createUser·p0.9999: 11.749 ms/op
                 createUser·p1.00:   12.141 ms/op

Iteration   2: 3.057 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.229 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  9.503 ms/op
                 createUser·p0.9999: 13.707 ms/op
                 createUser·p1.00:   15.663 ms/op

Iteration   3: 3.069 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.633 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   4.219 ms/op
                 createUser·p0.999:  6.153 ms/op
                 createUser·p0.9999: 22.170 ms/op
                 createUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313474
  mean =      3.063 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30260 
    [ 2.500,  5.000) = 282264 
    [ 5.000,  7.500) = 604 
    [ 7.500, 10.000) = 122 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.229 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      8.352 ms/op
     p(99.9900) =     21.593 ms/op
     p(99.9990) =     22.376 ms/op
     p(99.9999) =     22.446 ms/op
    p(100.0000) =     22.446 ms/op


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
# Warmup Iteration   1: 3.369 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.046 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.966 ±(99.9%) 0.006 ms/op
Iteration   1: 2.939 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.699 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   4.121 ms/op
                 existUser·p0.999:  7.603 ms/op
                 existUser·p0.9999: 12.916 ms/op
                 existUser·p1.00:   13.435 ms/op

Iteration   2: 2.928 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.668 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.100 ms/op
                 existUser·p0.999:  5.112 ms/op
                 existUser·p0.9999: 14.683 ms/op
                 existUser·p1.00:   15.139 ms/op

Iteration   3: 2.801 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.623 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.256 ms/op
                 existUser·p0.95:   3.453 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  6.380 ms/op
                 existUser·p0.9999: 19.595 ms/op
                 existUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332496
  mean =      2.888 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53747 
    [ 2.500,  5.000) = 278050 
    [ 5.000,  7.500) = 457 
    [ 7.500, 10.000) = 63 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.623 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.666 ms/op
     p(99.0000) =      4.170 ms/op
     p(99.9000) =      6.750 ms/op
     p(99.9900) =     18.956 ms/op
     p(99.9990) =     19.978 ms/op
     p(99.9999) =     20.054 ms/op
    p(100.0000) =     20.054 ms/op


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
# Warmup Iteration   1: 3.819 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.125 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.006 ms/op
Iteration   1: 3.061 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.708 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  8.218 ms/op
                 getUser·p0.9999: 17.600 ms/op
                 getUser·p1.00:   19.005 ms/op

Iteration   2: 2.967 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.689 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   4.186 ms/op
                 getUser·p0.999:  5.900 ms/op
                 getUser·p0.9999: 13.557 ms/op
                 getUser·p1.00:   13.861 ms/op

Iteration   3: 2.957 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.349 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.428 ms/op
                 getUser·p0.95:   3.625 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  7.237 ms/op
                 getUser·p0.9999: 23.462 ms/op
                 getUser·p1.00:   25.330 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320405
  mean =      2.994 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34315 
    [ 2.500,  5.000) = 285122 
    [ 5.000,  7.500) = 686 
    [ 7.500, 10.000) = 90 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.349 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      7.025 ms/op
     p(99.9900) =     22.275 ms/op
     p(99.9990) =     25.330 ms/op
     p(99.9999) =     25.330 ms/op
    p(100.0000) =     25.330 ms/op


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
# Warmup Iteration   1: 4.103 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.091 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.974 ±(99.9%) 0.012 ms/op
Iteration   1: 4.005 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.597 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  12.681 ms/op
                 listUser·p0.9999: 18.614 ms/op
                 listUser·p1.00:   19.268 ms/op

Iteration   2: 3.938 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.237 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  13.061 ms/op
                 listUser·p0.9999: 23.888 ms/op
                 listUser·p1.00:   24.248 ms/op

Iteration   3: 3.827 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.069 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   5.341 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  16.734 ms/op
                 listUser·p0.9999: 26.465 ms/op
                 listUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244655
  mean =      3.922 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5268 
    [ 2.500,  5.000) = 214129 
    [ 5.000,  7.500) = 23956 
    [ 7.500, 10.000) = 720 
    [10.000, 12.500) = 207 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.597 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      5.022 ms/op
     p(95.0000) =      5.546 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     15.500 ms/op
     p(99.9900) =     25.985 ms/op
     p(99.9990) =     27.412 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.381 ± 7.697  ops/ms
ClientGrpc.existUser                       thrpt       3  11.068 ± 3.461  ops/ms
ClientGrpc.getUser                         thrpt       3  10.640 ± 1.678  ops/ms
ClientGrpc.listUser                        thrpt       3   8.186 ± 1.315  ops/ms
ClientGrpc.createUser                       avgt       3   3.102 ± 0.806   ms/op
ClientGrpc.existUser                        avgt       3   2.867 ± 0.390   ms/op
ClientGrpc.getUser                          avgt       3   2.969 ± 0.988   ms/op
ClientGrpc.listUser                         avgt       3   3.955 ± 0.463   ms/op
ClientGrpc.createUser                     sample  313474   3.063 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.229           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.035           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.690           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.887           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.284           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.352           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.593           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.446           ms/op
ClientGrpc.existUser                      sample  332496   2.888 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.623           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.892           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.457           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.666           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.170           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.750           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.956           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.054           ms/op
ClientGrpc.getUser                        sample  320405   2.994 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.349           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.990           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.568           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.781           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.276           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.025           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.275           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.330           ms/op
ClientGrpc.listUser                       sample  244655   3.922 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.597           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.752           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.022           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.546           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.717           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.500           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.985           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.525           ms/op
