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
# Warmup Iteration   1: 2.296 ops/ms
# Warmup Iteration   2: 5.281 ops/ms
# Warmup Iteration   3: 6.893 ops/ms
Iteration   1: 7.179 ops/ms
Iteration   2: 7.143 ops/ms
Iteration   3: 7.445 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.255 ±(99.9%) 3.008 ops/ms [Average]
  (min, avg, max) = (7.143, 7.255, 7.445), stdev = 0.165
  CI (99.9%): [4.247, 10.263] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 5.026 ops/ms
# Warmup Iteration   2: 7.493 ops/ms
# Warmup Iteration   3: 7.818 ops/ms
Iteration   1: 7.573 ops/ms
Iteration   2: 8.158 ops/ms
Iteration   3: 7.962 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.898 ±(99.9%) 5.435 ops/ms [Average]
  (min, avg, max) = (7.573, 7.898, 8.158), stdev = 0.298
  CI (99.9%): [2.463, 13.332] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.834 ops/ms
# Warmup Iteration   2: 6.849 ops/ms
# Warmup Iteration   3: 7.504 ops/ms
Iteration   1: 7.153 ops/ms
Iteration   2: 7.603 ops/ms
Iteration   3: 7.315 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.357 ±(99.9%) 4.158 ops/ms [Average]
  (min, avg, max) = (7.153, 7.357, 7.603), stdev = 0.228
  CI (99.9%): [3.199, 11.515] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.688 ops/ms
# Warmup Iteration   2: 5.239 ops/ms
# Warmup Iteration   3: 5.605 ops/ms
Iteration   1: 5.683 ops/ms
Iteration   2: 5.539 ops/ms
Iteration   3: 5.631 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.618 ±(99.9%) 1.329 ops/ms [Average]
  (min, avg, max) = (5.539, 5.618, 5.683), stdev = 0.073
  CI (99.9%): [4.289, 6.947] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.499 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.760 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.467 ±(99.9%) 0.003 ms/op
Iteration   1: 4.470 ±(99.9%) 0.003 ms/op
Iteration   2: 4.409 ±(99.9%) 0.003 ms/op
Iteration   3: 4.391 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.423 ±(99.9%) 0.754 ms/op [Average]
  (min, avg, max) = (4.391, 4.423, 4.470), stdev = 0.041
  CI (99.9%): [3.670, 5.177] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.232 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.299 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.039 ±(99.9%) 0.004 ms/op
Iteration   1: 3.903 ±(99.9%) 0.005 ms/op
Iteration   2: 3.975 ±(99.9%) 0.003 ms/op
Iteration   3: 3.902 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.927 ±(99.9%) 0.765 ms/op [Average]
  (min, avg, max) = (3.902, 3.927, 3.975), stdev = 0.042
  CI (99.9%): [3.162, 4.692] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.487 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.739 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.409 ±(99.9%) 0.003 ms/op
Iteration   1: 4.348 ±(99.9%) 0.003 ms/op
Iteration   2: 4.203 ±(99.9%) 0.003 ms/op
Iteration   3: 4.174 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.242 ±(99.9%) 1.699 ms/op [Average]
  (min, avg, max) = (4.174, 4.242, 4.348), stdev = 0.093
  CI (99.9%): [2.543, 5.940] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.181 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 6.292 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.869 ±(99.9%) 0.030 ms/op
Iteration   1: 5.734 ±(99.9%) 0.017 ms/op
Iteration   2: 5.614 ±(99.9%) 0.018 ms/op
Iteration   3: 5.594 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.647 ±(99.9%) 1.374 ms/op [Average]
  (min, avg, max) = (5.594, 5.647, 5.734), stdev = 0.075
  CI (99.9%): [4.273, 7.021] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.972 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 4.700 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.439 ±(99.9%) 0.014 ms/op
Iteration   1: 4.300 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.059 ms/op
                 createUser·p0.50:   4.141 ms/op
                 createUser·p0.90:   5.480 ms/op
                 createUser·p0.95:   6.078 ms/op
                 createUser·p0.99:   7.794 ms/op
                 createUser·p0.999:  14.041 ms/op
                 createUser·p0.9999: 23.448 ms/op
                 createUser·p1.00:   23.822 ms/op

Iteration   2: 4.253 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.935 ms/op
                 createUser·p0.50:   4.116 ms/op
                 createUser·p0.90:   5.472 ms/op
                 createUser·p0.95:   6.078 ms/op
                 createUser·p0.99:   7.782 ms/op
                 createUser·p0.999:  15.345 ms/op
                 createUser·p0.9999: 24.853 ms/op
                 createUser·p1.00:   25.919 ms/op

Iteration   3: 4.276 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.938 ms/op
                 createUser·p0.50:   4.170 ms/op
                 createUser·p0.90:   5.480 ms/op
                 createUser·p0.95:   6.078 ms/op
                 createUser·p0.99:   8.110 ms/op
                 createUser·p0.999:  13.179 ms/op
                 createUser·p0.9999: 26.380 ms/op
                 createUser·p1.00:   27.820 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 224356
  mean =      4.276 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6978 
    [ 2.500,  5.000) = 177290 
    [ 5.000,  7.500) = 37052 
    [ 7.500, 10.000) = 2352 
    [10.000, 12.500) = 321 
    [12.500, 15.000) = 210 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.935 ms/op
     p(50.0000) =      4.141 ms/op
     p(90.0000) =      5.480 ms/op
     p(95.0000) =      6.078 ms/op
     p(99.0000) =      7.889 ms/op
     p(99.9000) =     14.074 ms/op
     p(99.9900) =     25.807 ms/op
     p(99.9990) =     27.673 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.055 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.341 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.121 ±(99.9%) 0.013 ms/op
Iteration   1: 3.970 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.756 ms/op
                 existUser·p0.50:   3.826 ms/op
                 existUser·p0.90:   5.046 ms/op
                 existUser·p0.95:   5.661 ms/op
                 existUser·p0.99:   7.397 ms/op
                 existUser·p0.999:  11.261 ms/op
                 existUser·p0.9999: 18.282 ms/op
                 existUser·p1.00:   20.513 ms/op

Iteration   2: 4.175 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.969 ms/op
                 existUser·p0.50:   3.998 ms/op
                 existUser·p0.90:   5.218 ms/op
                 existUser·p0.95:   5.849 ms/op
                 existUser·p0.99:   8.225 ms/op
                 existUser·p0.999:  13.260 ms/op
                 existUser·p0.9999: 22.468 ms/op
                 existUser·p1.00:   23.003 ms/op

Iteration   3: 4.261 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.130 ms/op
                 existUser·p0.50:   4.080 ms/op
                 existUser·p0.90:   5.407 ms/op
                 existUser·p0.95:   6.078 ms/op
                 existUser·p0.99:   8.651 ms/op
                 existUser·p0.999:  12.435 ms/op
                 existUser·p0.9999: 29.327 ms/op
                 existUser·p1.00:   29.426 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 232415
  mean =      4.132 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5216 
    [ 2.500,  5.000) = 196205 
    [ 5.000,  7.500) = 27763 
    [ 7.500, 10.000) = 2540 
    [10.000, 12.500) = 443 
    [12.500, 15.000) = 140 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.756 ms/op
     p(50.0000) =      3.961 ms/op
     p(90.0000) =      5.235 ms/op
     p(95.0000) =      5.849 ms/op
     p(99.0000) =      8.077 ms/op
     p(99.9000) =     12.698 ms/op
     p(99.9900) =     28.492 ms/op
     p(99.9990) =     29.382 ms/op
     p(99.9999) =     29.426 ms/op
    p(100.0000) =     29.426 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.474 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.555 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.268 ±(99.9%) 0.013 ms/op
Iteration   1: 4.294 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.388 ms/op
                 getUser·p0.50:   4.125 ms/op
                 getUser·p0.90:   5.480 ms/op
                 getUser·p0.95:   6.038 ms/op
                 getUser·p0.99:   7.766 ms/op
                 getUser·p0.999:  11.699 ms/op
                 getUser·p0.9999: 32.721 ms/op
                 getUser·p1.00:   33.882 ms/op

Iteration   2: 4.431 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.944 ms/op
                 getUser·p0.50:   4.260 ms/op
                 getUser·p0.90:   5.571 ms/op
                 getUser·p0.95:   6.193 ms/op
                 getUser·p0.99:   8.552 ms/op
                 getUser·p0.999:  16.564 ms/op
                 getUser·p0.9999: 26.945 ms/op
                 getUser·p1.00:   27.361 ms/op

Iteration   3: 4.258 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.524 ms/op
                 getUser·p0.50:   4.096 ms/op
                 getUser·p0.90:   5.456 ms/op
                 getUser·p0.95:   6.021 ms/op
                 getUser·p0.99:   7.854 ms/op
                 getUser·p0.999:  11.745 ms/op
                 getUser·p0.9999: 28.639 ms/op
                 getUser·p1.00:   28.934 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 221919
  mean =      4.327 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3843 
    [ 2.500,  5.000) = 176358 
    [ 5.000,  7.500) = 38484 
    [ 7.500, 10.000) = 2692 
    [10.000, 12.500) = 303 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.388 ms/op
     p(50.0000) =      4.157 ms/op
     p(90.0000) =      5.497 ms/op
     p(95.0000) =      6.087 ms/op
     p(99.0000) =      8.028 ms/op
     p(99.9000) =     13.643 ms/op
     p(99.9900) =     30.533 ms/op
     p(99.9990) =     32.983 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 7.721 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 6.448 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.855 ±(99.9%) 0.026 ms/op
Iteration   1: 5.829 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.815 ms/op
                 listUser·p0.50:   5.390 ms/op
                 listUser·p0.90:   8.225 ms/op
                 listUser·p0.95:   9.306 ms/op
                 listUser·p0.99:   11.878 ms/op
                 listUser·p0.999:  16.975 ms/op
                 listUser·p0.9999: 26.903 ms/op
                 listUser·p1.00:   27.132 ms/op

Iteration   2: 5.586 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.028 ms/op
                 listUser·p0.50:   5.186 ms/op
                 listUser·p0.90:   7.619 ms/op
                 listUser·p0.95:   8.618 ms/op
                 listUser·p0.99:   11.682 ms/op
                 listUser·p0.999:  20.758 ms/op
                 listUser·p0.9999: 43.385 ms/op
                 listUser·p1.00:   44.368 ms/op

Iteration   3: 5.516 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.581 ms/op
                 listUser·p0.50:   5.095 ms/op
                 listUser·p0.90:   7.795 ms/op
                 listUser·p0.95:   8.864 ms/op
                 listUser·p0.99:   11.223 ms/op
                 listUser·p0.999:  30.514 ms/op
                 listUser·p0.9999: 36.465 ms/op
                 listUser·p1.00:   38.207 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 170171
  mean =      5.640 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 72312 
    [ 5.000, 10.000) = 93467 
    [10.000, 15.000) = 3876 
    [15.000, 20.000) = 292 
    [20.000, 25.000) = 86 
    [25.000, 30.000) = 43 
    [30.000, 35.000) = 54 
    [35.000, 40.000) = 32 
    [40.000, 45.000) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.028 ms/op
     p(50.0000) =      5.218 ms/op
     p(90.0000) =      7.881 ms/op
     p(95.0000) =      8.962 ms/op
     p(99.0000) =     11.567 ms/op
     p(99.9000) =     20.775 ms/op
     p(99.9900) =     36.437 ms/op
     p(99.9990) =     44.368 ms/op
     p(99.9999) =     44.368 ms/op
    p(100.0000) =     44.368 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.255 ± 3.008  ops/ms
ClientGrpc.existUser                       thrpt       3   7.898 ± 5.435  ops/ms
ClientGrpc.getUser                         thrpt       3   7.357 ± 4.158  ops/ms
ClientGrpc.listUser                        thrpt       3   5.618 ± 1.329  ops/ms
ClientGrpc.createUser                       avgt       3   4.423 ± 0.754   ms/op
ClientGrpc.existUser                        avgt       3   3.927 ± 0.765   ms/op
ClientGrpc.getUser                          avgt       3   4.242 ± 1.699   ms/op
ClientGrpc.listUser                         avgt       3   5.647 ± 1.374   ms/op
ClientGrpc.createUser                     sample  224356   4.276 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.935           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.141           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.480           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.078           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.889           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.074           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.807           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.820           ms/op
ClientGrpc.existUser                      sample  232415   4.132 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.756           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.961           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.235           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.849           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.077           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.698           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          28.492           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.426           ms/op
ClientGrpc.getUser                        sample  221919   4.327 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.388           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.157           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.497           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.087           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.028           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.643           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          30.533           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.882           ms/op
ClientGrpc.listUser                       sample  170171   5.640 ± 0.015   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.028           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.218           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.881           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.962           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.567           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.775           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          36.437           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          44.368           ms/op
