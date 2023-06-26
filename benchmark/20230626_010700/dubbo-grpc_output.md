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
# Warmup Iteration   1: 2.914 ops/ms
# Warmup Iteration   2: 5.932 ops/ms
# Warmup Iteration   3: 7.736 ops/ms
Iteration   1: 8.303 ops/ms
Iteration   2: 8.077 ops/ms
Iteration   3: 8.332 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.237 ±(99.9%) 2.553 ops/ms [Average]
  (min, avg, max) = (8.077, 8.237, 8.332), stdev = 0.140
  CI (99.9%): [5.684, 10.791] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.290 ops/ms
# Warmup Iteration   2: 7.991 ops/ms
# Warmup Iteration   3: 8.690 ops/ms
Iteration   1: 9.099 ops/ms
Iteration   2: 8.879 ops/ms
Iteration   3: 8.875 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.951 ±(99.9%) 2.337 ops/ms [Average]
  (min, avg, max) = (8.875, 8.951, 9.099), stdev = 0.128
  CI (99.9%): [6.614, 11.288] (assumes normal distribution)


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
# Warmup Iteration   1: 5.139 ops/ms
# Warmup Iteration   2: 7.877 ops/ms
# Warmup Iteration   3: 8.144 ops/ms
Iteration   1: 8.327 ops/ms
Iteration   2: 8.455 ops/ms
Iteration   3: 8.545 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.442 ±(99.9%) 1.999 ops/ms [Average]
  (min, avg, max) = (8.327, 8.442, 8.545), stdev = 0.110
  CI (99.9%): [6.443, 10.441] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 4.444 ops/ms
# Warmup Iteration   2: 5.932 ops/ms
# Warmup Iteration   3: 6.361 ops/ms
Iteration   1: 6.521 ops/ms
Iteration   2: 6.327 ops/ms
Iteration   3: 6.517 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.455 ±(99.9%) 2.030 ops/ms [Average]
  (min, avg, max) = (6.327, 6.455, 6.521), stdev = 0.111
  CI (99.9%): [4.425, 8.485] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.492 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.050 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.910 ±(99.9%) 0.004 ms/op
Iteration   1: 3.834 ±(99.9%) 0.003 ms/op
Iteration   2: 3.770 ±(99.9%) 0.003 ms/op
Iteration   3: 3.800 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.801 ±(99.9%) 0.585 ms/op [Average]
  (min, avg, max) = (3.770, 3.801, 3.834), stdev = 0.032
  CI (99.9%): [3.216, 4.387] (assumes normal distribution)


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
# Warmup Iteration   1: 5.248 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.763 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.535 ±(99.9%) 0.003 ms/op
Iteration   1: 3.680 ±(99.9%) 0.009 ms/op
Iteration   2: 3.581 ±(99.9%) 0.002 ms/op
Iteration   3: 3.483 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.581 ±(99.9%) 1.796 ms/op [Average]
  (min, avg, max) = (3.483, 3.581, 3.680), stdev = 0.098
  CI (99.9%): [1.785, 5.377] (assumes normal distribution)


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
# Warmup Iteration   1: 5.294 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.107 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.965 ±(99.9%) 0.002 ms/op
Iteration   1: 3.936 ±(99.9%) 0.004 ms/op
Iteration   2: 3.880 ±(99.9%) 0.003 ms/op
Iteration   3: 3.739 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.852 ±(99.9%) 1.853 ms/op [Average]
  (min, avg, max) = (3.739, 3.852, 3.936), stdev = 0.102
  CI (99.9%): [1.999, 5.704] (assumes normal distribution)


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
# Warmup Iteration   1: 7.246 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 5.460 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.989 ±(99.9%) 0.021 ms/op
Iteration   1: 4.806 ±(99.9%) 0.008 ms/op
Iteration   2: 4.976 ±(99.9%) 0.015 ms/op
Iteration   3: 4.949 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.910 ±(99.9%) 1.662 ms/op [Average]
  (min, avg, max) = (4.806, 4.910, 4.976), stdev = 0.091
  CI (99.9%): [3.249, 6.572] (assumes normal distribution)


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
# Warmup Iteration   1: 5.872 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.266 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.954 ±(99.9%) 0.012 ms/op
Iteration   1: 3.966 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.922 ms/op
                 createUser·p0.50:   3.781 ms/op
                 createUser·p0.90:   4.874 ms/op
                 createUser·p0.95:   5.358 ms/op
                 createUser·p0.99:   7.332 ms/op
                 createUser·p0.999:  16.308 ms/op
                 createUser·p0.9999: 60.813 ms/op
                 createUser·p1.00:   63.439 ms/op

Iteration   2: 3.790 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.035 ms/op
                 createUser·p0.50:   3.690 ms/op
                 createUser·p0.90:   4.669 ms/op
                 createUser·p0.95:   5.063 ms/op
                 createUser·p0.99:   6.447 ms/op
                 createUser·p0.999:  10.496 ms/op
                 createUser·p0.9999: 18.715 ms/op
                 createUser·p1.00:   19.071 ms/op

Iteration   3: 3.758 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.541 ms/op
                 createUser·p0.50:   3.678 ms/op
                 createUser·p0.90:   4.407 ms/op
                 createUser·p0.95:   4.751 ms/op
                 createUser·p0.99:   5.833 ms/op
                 createUser·p0.999:  17.367 ms/op
                 createUser·p0.9999: 24.183 ms/op
                 createUser·p1.00:   28.082 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 250054
  mean =      3.836 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 236122 
    [ 5.000, 10.000) = 13494 
    [10.000, 15.000) = 208 
    [15.000, 20.000) = 141 
    [20.000, 25.000) = 50 
    [25.000, 30.000) = 4 
    [30.000, 35.000) = 6 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 1 
    [50.000, 55.000) = 4 
    [55.000, 60.000) = 8 
    [60.000, 65.000) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.541 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      5.071 ms/op
     p(99.0000) =      6.595 ms/op
     p(99.9000) =     14.201 ms/op
     p(99.9900) =     51.021 ms/op
     p(99.9990) =     62.291 ms/op
     p(99.9999) =     63.439 ms/op
    p(100.0000) =     63.439 ms/op


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
# Warmup Iteration   1: 5.065 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.939 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.631 ±(99.9%) 0.008 ms/op
Iteration   1: 3.673 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.655 ms/op
                 existUser·p0.50:   3.564 ms/op
                 existUser·p0.90:   4.448 ms/op
                 existUser·p0.95:   4.825 ms/op
                 existUser·p0.99:   6.226 ms/op
                 existUser·p0.999:  9.093 ms/op
                 existUser·p0.9999: 20.925 ms/op
                 existUser·p1.00:   21.201 ms/op

Iteration   2: 3.569 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.943 ms/op
                 existUser·p0.50:   3.523 ms/op
                 existUser·p0.90:   4.133 ms/op
                 existUser·p0.95:   4.448 ms/op
                 existUser·p0.99:   5.628 ms/op
                 existUser·p0.999:  7.949 ms/op
                 existUser·p0.9999: 20.547 ms/op
                 existUser·p1.00:   22.708 ms/op

Iteration   3: 3.664 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.005 ms/op
                 existUser·p0.50:   3.580 ms/op
                 existUser·p0.90:   4.325 ms/op
                 existUser·p0.95:   4.637 ms/op
                 existUser·p0.99:   5.784 ms/op
                 existUser·p0.999:  10.633 ms/op
                 existUser·p0.9999: 25.338 ms/op
                 existUser·p1.00:   25.592 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 264142
  mean =      3.635 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5567 
    [ 2.500,  5.000) = 251084 
    [ 5.000,  7.500) = 6692 
    [ 7.500, 10.000) = 549 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.655 ms/op
     p(50.0000) =      3.551 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =      9.929 ms/op
     p(99.9900) =     24.969 ms/op
     p(99.9990) =     25.559 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


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
# Warmup Iteration   1: 5.468 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.073 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.817 ±(99.9%) 0.009 ms/op
Iteration   1: 3.785 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.069 ms/op
                 getUser·p0.50:   3.695 ms/op
                 getUser·p0.90:   4.751 ms/op
                 getUser·p0.95:   5.128 ms/op
                 getUser·p0.99:   6.414 ms/op
                 getUser·p0.999:  9.421 ms/op
                 getUser·p0.9999: 16.974 ms/op
                 getUser·p1.00:   17.269 ms/op

Iteration   2: 3.720 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.085 ms/op
                 getUser·p0.50:   3.629 ms/op
                 getUser·p0.90:   4.358 ms/op
                 getUser·p0.95:   4.801 ms/op
                 getUser·p0.99:   6.267 ms/op
                 getUser·p0.999:  13.795 ms/op
                 getUser·p0.9999: 17.708 ms/op
                 getUser·p1.00:   18.547 ms/op

Iteration   3: 3.800 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.816 ms/op
                 getUser·p0.50:   3.703 ms/op
                 getUser·p0.90:   4.538 ms/op
                 getUser·p0.95:   4.956 ms/op
                 getUser·p0.99:   6.095 ms/op
                 getUser·p0.999:  9.945 ms/op
                 getUser·p0.9999: 18.355 ms/op
                 getUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 254721
  mean =      3.768 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6778 
    [ 2.500,  5.000) = 235432 
    [ 5.000,  7.500) = 11604 
    [ 7.500, 10.000) = 627 
    [10.000, 12.500) = 120 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.816 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      6.250 ms/op
     p(99.9000) =     10.256 ms/op
     p(99.9900) =     17.843 ms/op
     p(99.9990) =     21.031 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


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
# Warmup Iteration   1: 6.327 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.327 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.849 ±(99.9%) 0.015 ms/op
Iteration   1: 4.786 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.294 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.849 ms/op
                 listUser·p0.95:   6.726 ms/op
                 listUser·p0.99:   8.438 ms/op
                 listUser·p0.999:  17.143 ms/op
                 listUser·p0.9999: 24.816 ms/op
                 listUser·p1.00:   25.592 ms/op

Iteration   2: 4.885 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.630 ms/op
                 listUser·p0.50:   4.686 ms/op
                 listUser·p0.90:   5.800 ms/op
                 listUser·p0.95:   6.726 ms/op
                 listUser·p0.99:   8.700 ms/op
                 listUser·p0.999:  19.202 ms/op
                 listUser·p0.9999: 26.441 ms/op
                 listUser·p1.00:   26.706 ms/op

Iteration   3: 4.755 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.194 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.800 ms/op
                 listUser·p0.95:   6.824 ms/op
                 listUser·p0.99:   9.142 ms/op
                 listUser·p0.999:  20.008 ms/op
                 listUser·p0.9999: 23.138 ms/op
                 listUser·p1.00:   24.314 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 199689
  mean =      4.808 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 108 
    [ 2.500,  5.000) = 149004 
    [ 5.000,  7.500) = 45129 
    [ 7.500, 10.000) = 4579 
    [10.000, 12.500) = 428 
    [12.500, 15.000) = 120 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.194 ms/op
     p(50.0000) =      4.620 ms/op
     p(90.0000) =      5.816 ms/op
     p(95.0000) =      6.750 ms/op
     p(99.0000) =      8.765 ms/op
     p(99.9000) =     19.343 ms/op
     p(99.9900) =     25.264 ms/op
     p(99.9990) =     26.543 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.237 ± 2.553  ops/ms
ClientGrpc.existUser                       thrpt       3   8.951 ± 2.337  ops/ms
ClientGrpc.getUser                         thrpt       3   8.442 ± 1.999  ops/ms
ClientGrpc.listUser                        thrpt       3   6.455 ± 2.030  ops/ms
ClientGrpc.createUser                       avgt       3   3.801 ± 0.585   ms/op
ClientGrpc.existUser                        avgt       3   3.581 ± 1.796   ms/op
ClientGrpc.getUser                          avgt       3   3.852 ± 1.853   ms/op
ClientGrpc.listUser                         avgt       3   4.910 ± 1.662   ms/op
ClientGrpc.createUser                     sample  250054   3.836 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.541           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.715           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.653           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.071           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.595           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.201           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          51.021           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          63.439           ms/op
ClientGrpc.existUser                      sample  264142   3.635 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.655           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.551           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.309           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.653           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.898           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.929           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.969           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.592           ms/op
ClientGrpc.getUser                        sample  254721   3.768 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.816           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.674           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.563           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.989           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.250           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.256           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.843           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.201           ms/op
ClientGrpc.listUser                       sample  199689   4.808 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.194           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.620           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.816           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.750           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.765           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.343           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.264           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.706           ms/op
