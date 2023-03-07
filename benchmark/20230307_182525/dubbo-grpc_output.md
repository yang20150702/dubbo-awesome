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
# Warmup Iteration   1: 2.980 ops/ms
# Warmup Iteration   2: 6.482 ops/ms
# Warmup Iteration   3: 8.108 ops/ms
Iteration   1: 8.387 ops/ms
Iteration   2: 8.414 ops/ms
Iteration   3: 8.524 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.442 ±(99.9%) 1.326 ops/ms [Average]
  (min, avg, max) = (8.387, 8.442, 8.524), stdev = 0.073
  CI (99.9%): [7.116, 9.767] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.605 ops/ms
# Warmup Iteration   2: 8.332 ops/ms
# Warmup Iteration   3: 8.947 ops/ms
Iteration   1: 8.843 ops/ms
Iteration   2: 9.284 ops/ms
Iteration   3: 8.953 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.027 ±(99.9%) 4.192 ops/ms [Average]
  (min, avg, max) = (8.843, 9.027, 9.284), stdev = 0.230
  CI (99.9%): [4.834, 13.219] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.554 ops/ms
# Warmup Iteration   2: 8.289 ops/ms
# Warmup Iteration   3: 8.503 ops/ms
Iteration   1: 8.430 ops/ms
Iteration   2: 8.522 ops/ms
Iteration   3: 8.460 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.470 ±(99.9%) 0.857 ops/ms [Average]
  (min, avg, max) = (8.430, 8.470, 8.522), stdev = 0.047
  CI (99.9%): [7.614, 9.327] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.483 ops/ms
# Warmup Iteration   2: 6.304 ops/ms
# Warmup Iteration   3: 6.697 ops/ms
Iteration   1: 6.950 ops/ms
Iteration   2: 6.859 ops/ms
Iteration   3: 6.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.867 ±(99.9%) 1.443 ops/ms [Average]
  (min, avg, max) = (6.793, 6.867, 6.950), stdev = 0.079
  CI (99.9%): [5.425, 8.310] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.385 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.952 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.825 ±(99.9%) 0.006 ms/op
Iteration   1: 3.783 ±(99.9%) 0.003 ms/op
Iteration   2: 3.898 ±(99.9%) 0.003 ms/op
Iteration   3: 3.812 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.831 ±(99.9%) 1.088 ms/op [Average]
  (min, avg, max) = (3.783, 3.831, 3.898), stdev = 0.060
  CI (99.9%): [2.743, 4.919] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.929 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.815 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.628 ±(99.9%) 0.003 ms/op
Iteration   1: 3.640 ±(99.9%) 0.003 ms/op
Iteration   2: 3.663 ±(99.9%) 0.003 ms/op
Iteration   3: 3.538 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.614 ±(99.9%) 1.221 ms/op [Average]
  (min, avg, max) = (3.538, 3.614, 3.663), stdev = 0.067
  CI (99.9%): [2.393, 4.834] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.481 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.060 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.877 ±(99.9%) 0.003 ms/op
Iteration   1: 3.887 ±(99.9%) 0.003 ms/op
Iteration   2: 3.784 ±(99.9%) 0.005 ms/op
Iteration   3: 3.835 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.835 ±(99.9%) 0.942 ms/op [Average]
  (min, avg, max) = (3.784, 3.835, 3.887), stdev = 0.052
  CI (99.9%): [2.893, 4.777] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 7.125 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 5.105 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.931 ±(99.9%) 0.020 ms/op
Iteration   1: 4.862 ±(99.9%) 0.010 ms/op
Iteration   2: 4.689 ±(99.9%) 0.006 ms/op
Iteration   3: 4.542 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.698 ±(99.9%) 2.925 ms/op [Average]
  (min, avg, max) = (4.542, 4.698, 4.862), stdev = 0.160
  CI (99.9%): [1.773, 7.623] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.474 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.040 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.876 ±(99.9%) 0.010 ms/op
Iteration   1: 3.882 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.943 ms/op
                 createUser·p0.50:   3.813 ms/op
                 createUser·p0.90:   4.710 ms/op
                 createUser·p0.95:   5.063 ms/op
                 createUser·p0.99:   6.273 ms/op
                 createUser·p0.999:  9.798 ms/op
                 createUser·p0.9999: 20.210 ms/op
                 createUser·p1.00:   20.283 ms/op

Iteration   2: 3.816 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.004 ms/op
                 createUser·p0.50:   3.744 ms/op
                 createUser·p0.90:   4.588 ms/op
                 createUser·p0.95:   4.923 ms/op
                 createUser·p0.99:   6.218 ms/op
                 createUser·p0.999:  12.656 ms/op
                 createUser·p0.9999: 22.827 ms/op
                 createUser·p1.00:   23.331 ms/op

Iteration   3: 3.857 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.613 ms/op
                 createUser·p0.50:   3.785 ms/op
                 createUser·p0.90:   4.702 ms/op
                 createUser·p0.95:   4.997 ms/op
                 createUser·p0.99:   5.991 ms/op
                 createUser·p0.999:  11.710 ms/op
                 createUser·p0.9999: 26.466 ms/op
                 createUser·p1.00:   26.739 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 249269
  mean =      3.852 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5849 
    [ 2.500,  5.000) = 230999 
    [ 5.000,  7.500) = 11264 
    [ 7.500, 10.000) = 787 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.613 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      6.169 ms/op
     p(99.9000) =     11.448 ms/op
     p(99.9900) =     25.299 ms/op
     p(99.9990) =     26.641 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.132 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.976 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.774 ±(99.9%) 0.011 ms/op
Iteration   1: 3.799 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.029 ms/op
                 existUser·p0.50:   3.748 ms/op
                 existUser·p0.90:   4.743 ms/op
                 existUser·p0.95:   5.038 ms/op
                 existUser·p0.99:   6.005 ms/op
                 existUser·p0.999:  9.287 ms/op
                 existUser·p0.9999: 15.755 ms/op
                 existUser·p1.00:   16.843 ms/op

Iteration   2: 3.742 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.801 ms/op
                 existUser·p0.50:   3.686 ms/op
                 existUser·p0.90:   4.596 ms/op
                 existUser·p0.95:   4.833 ms/op
                 existUser·p0.99:   5.431 ms/op
                 existUser·p0.999:  13.575 ms/op
                 existUser·p0.9999: 25.094 ms/op
                 existUser·p1.00:   25.526 ms/op

Iteration   3: 3.851 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.962 ms/op
                 existUser·p0.50:   3.772 ms/op
                 existUser·p0.90:   4.768 ms/op
                 existUser·p0.95:   5.054 ms/op
                 existUser·p0.99:   6.455 ms/op
                 existUser·p0.999:  9.482 ms/op
                 existUser·p0.9999: 19.814 ms/op
                 existUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 252876
  mean =      3.797 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7751 
    [ 2.500,  5.000) = 233260 
    [ 5.000,  7.500) = 11032 
    [ 7.500, 10.000) = 607 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.801 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.702 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =      9.601 ms/op
     p(99.9900) =     24.698 ms/op
     p(99.9990) =     25.459 ms/op
     p(99.9999) =     25.526 ms/op
    p(100.0000) =     25.526 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.304 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.149 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.165 ±(99.9%) 0.056 ms/op
Iteration   1: 9.662 ±(99.9%) 0.092 ms/op
                 getUser·p0.00:   1.587 ms/op
                 getUser·p0.50:   10.093 ms/op
                 getUser·p0.90:   16.269 ms/op
                 getUser·p0.95:   17.695 ms/op
                 getUser·p0.99:   20.939 ms/op
                 getUser·p0.999:  26.235 ms/op
                 getUser·p0.9999: 31.406 ms/op
                 getUser·p1.00:   34.734 ms/op

Iteration   2: 4.367 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   1.124 ms/op
                 getUser·p0.50:   3.912 ms/op
                 getUser·p0.90:   5.226 ms/op
                 getUser·p0.95:   7.807 ms/op
                 getUser·p0.99:   15.548 ms/op
                 getUser·p0.999:  23.267 ms/op
                 getUser·p0.9999: 75.497 ms/op
                 getUser·p1.00:   76.546 ms/op

Iteration   3: 4.004 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.850 ms/op
                 getUser·p0.50:   3.891 ms/op
                 getUser·p0.90:   4.923 ms/op
                 getUser·p0.95:   5.333 ms/op
                 getUser·p0.99:   7.102 ms/op
                 getUser·p0.999:  12.995 ms/op
                 getUser·p0.9999: 27.132 ms/op
                 getUser·p1.00:   27.329 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 186210
  mean =      5.153 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 147993 
    [ 5.000, 10.000) = 18822 
    [10.000, 15.000) = 12836 
    [15.000, 20.000) = 5854 
    [20.000, 25.000) = 567 
    [25.000, 30.000) = 86 
    [30.000, 35.000) = 20 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 0 
    [65.000, 70.000) = 0 
    [70.000, 75.000) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.850 ms/op
     p(50.0000) =      4.022 ms/op
     p(90.0000) =     10.369 ms/op
     p(95.0000) =     13.959 ms/op
     p(99.0000) =     17.891 ms/op
     p(99.9000) =     23.717 ms/op
     p(99.9900) =     74.205 ms/op
     p(99.9990) =     76.546 ms/op
     p(99.9999) =     76.546 ms/op
    p(100.0000) =     76.546 ms/op


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
# Warmup Iteration   1: 7.329 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 5.208 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.882 ±(99.9%) 0.016 ms/op
Iteration   1: 4.560 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.634 ms/op
                 listUser·p0.50:   4.391 ms/op
                 listUser·p0.90:   5.661 ms/op
                 listUser·p0.95:   6.611 ms/op
                 listUser·p0.99:   8.438 ms/op
                 listUser·p0.999:  14.449 ms/op
                 listUser·p0.9999: 17.989 ms/op
                 listUser·p1.00:   19.857 ms/op

Iteration   2: 4.552 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.225 ms/op
                 listUser·p0.50:   4.383 ms/op
                 listUser·p0.90:   5.382 ms/op
                 listUser·p0.95:   6.463 ms/op
                 listUser·p0.99:   8.536 ms/op
                 listUser·p0.999:  16.994 ms/op
                 listUser·p0.9999: 21.035 ms/op
                 listUser·p1.00:   21.987 ms/op

Iteration   3: 4.889 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.282 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   6.218 ms/op
                 listUser·p0.95:   6.889 ms/op
                 listUser·p0.99:   8.913 ms/op
                 listUser·p0.999:  23.444 ms/op
                 listUser·p0.9999: 30.256 ms/op
                 listUser·p1.00:   31.130 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 205950
  mean =      4.662 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 477 
    [ 2.500,  5.000) = 161141 
    [ 5.000,  7.500) = 39055 
    [ 7.500, 10.000) = 4280 
    [10.000, 12.500) = 458 
    [12.500, 15.000) = 190 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.225 ms/op
     p(50.0000) =      4.465 ms/op
     p(90.0000) =      5.857 ms/op
     p(95.0000) =      6.693 ms/op
     p(99.0000) =      8.618 ms/op
     p(99.9000) =     18.974 ms/op
     p(99.9900) =     27.492 ms/op
     p(99.9990) =     31.124 ms/op
     p(99.9999) =     31.130 ms/op
    p(100.0000) =     31.130 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.442 ± 1.326  ops/ms
ClientGrpc.existUser                       thrpt       3   9.027 ± 4.192  ops/ms
ClientGrpc.getUser                         thrpt       3   8.470 ± 0.857  ops/ms
ClientGrpc.listUser                        thrpt       3   6.867 ± 1.443  ops/ms
ClientGrpc.createUser                       avgt       3   3.831 ± 1.088   ms/op
ClientGrpc.existUser                        avgt       3   3.614 ± 1.221   ms/op
ClientGrpc.getUser                          avgt       3   3.835 ± 0.942   ms/op
ClientGrpc.listUser                         avgt       3   4.698 ± 2.925   ms/op
ClientGrpc.createUser                     sample  249269   3.852 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.613           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.781           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.669           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.997           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.169           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.448           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.299           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.739           ms/op
ClientGrpc.existUser                      sample  252876   3.797 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.801           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.736           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.702           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.981           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.964           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.601           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.698           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.526           ms/op
ClientGrpc.getUser                        sample  186210   5.153 ± 0.027   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.850           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.022           ms/op
ClientGrpc.getUser:getUser·p0.90          sample          10.369           ms/op
ClientGrpc.getUser:getUser·p0.95          sample          13.959           ms/op
ClientGrpc.getUser:getUser·p0.99          sample          17.891           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          23.717           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          74.205           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          76.546           ms/op
ClientGrpc.listUser                       sample  205950   4.662 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.225           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.465           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.857           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.693           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.618           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.974           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.492           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.130           ms/op
