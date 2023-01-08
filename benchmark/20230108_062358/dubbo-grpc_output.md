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
# Warmup Iteration   1: 3.391 ops/ms
# Warmup Iteration   2: 7.093 ops/ms
# Warmup Iteration   3: 8.119 ops/ms
Iteration   1: 8.444 ops/ms
Iteration   2: 8.655 ops/ms
Iteration   3: 8.582 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.560 ±(99.9%) 1.960 ops/ms [Average]
  (min, avg, max) = (8.444, 8.560, 8.655), stdev = 0.107
  CI (99.9%): [6.600, 10.520] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.742 ops/ms
# Warmup Iteration   2: 8.405 ops/ms
# Warmup Iteration   3: 8.633 ops/ms
Iteration   1: 8.986 ops/ms
Iteration   2: 8.850 ops/ms
Iteration   3: 8.611 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.815 ±(99.9%) 3.464 ops/ms [Average]
  (min, avg, max) = (8.611, 8.815, 8.986), stdev = 0.190
  CI (99.9%): [5.352, 12.279] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.700 ops/ms
# Warmup Iteration   2: 8.306 ops/ms
# Warmup Iteration   3: 8.214 ops/ms
Iteration   1: 8.674 ops/ms
Iteration   2: 8.434 ops/ms
Iteration   3: 8.478 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.529 ±(99.9%) 2.331 ops/ms [Average]
  (min, avg, max) = (8.434, 8.529, 8.674), stdev = 0.128
  CI (99.9%): [6.198, 10.860] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.353 ops/ms
# Warmup Iteration   2: 6.332 ops/ms
# Warmup Iteration   3: 6.555 ops/ms
Iteration   1: 6.624 ops/ms
Iteration   2: 6.731 ops/ms
Iteration   3: 6.757 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.704 ±(99.9%) 1.286 ops/ms [Average]
  (min, avg, max) = (6.624, 6.704, 6.757), stdev = 0.070
  CI (99.9%): [5.418, 7.990] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.392 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.905 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.792 ±(99.9%) 0.003 ms/op
Iteration   1: 3.714 ±(99.9%) 0.003 ms/op
Iteration   2: 3.771 ±(99.9%) 0.002 ms/op
Iteration   3: 3.887 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.790 ±(99.9%) 1.607 ms/op [Average]
  (min, avg, max) = (3.714, 3.790, 3.887), stdev = 0.088
  CI (99.9%): [2.183, 5.398] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.033 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.817 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.800 ±(99.9%) 0.008 ms/op
Iteration   1: 3.603 ±(99.9%) 0.003 ms/op
Iteration   2: 3.582 ±(99.9%) 0.002 ms/op
Iteration   3: 3.620 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.602 ±(99.9%) 0.348 ms/op [Average]
  (min, avg, max) = (3.582, 3.602, 3.620), stdev = 0.019
  CI (99.9%): [3.254, 3.950] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.302 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.007 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.843 ±(99.9%) 0.004 ms/op
Iteration   1: 3.853 ±(99.9%) 0.003 ms/op
Iteration   2: 3.790 ±(99.9%) 0.006 ms/op
Iteration   3: 3.824 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.822 ±(99.9%) 0.579 ms/op [Average]
  (min, avg, max) = (3.790, 3.822, 3.853), stdev = 0.032
  CI (99.9%): [3.244, 4.401] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.373 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 5.064 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 4.844 ±(99.9%) 0.013 ms/op
Iteration   1: 4.688 ±(99.9%) 0.017 ms/op
Iteration   2: 4.846 ±(99.9%) 0.012 ms/op
Iteration   3: 4.653 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.729 ±(99.9%) 1.870 ms/op [Average]
  (min, avg, max) = (4.653, 4.729, 4.846), stdev = 0.103
  CI (99.9%): [2.859, 6.599] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.301 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.945 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.825 ±(99.9%) 0.009 ms/op
Iteration   1: 3.831 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.659 ms/op
                 createUser·p0.50:   3.785 ms/op
                 createUser·p0.90:   4.637 ms/op
                 createUser·p0.95:   4.899 ms/op
                 createUser·p0.99:   5.546 ms/op
                 createUser·p0.999:  12.074 ms/op
                 createUser·p0.9999: 28.574 ms/op
                 createUser·p1.00:   29.000 ms/op

Iteration   2: 3.838 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.950 ms/op
                 createUser·p0.50:   3.789 ms/op
                 createUser·p0.90:   4.645 ms/op
                 createUser·p0.95:   4.850 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  14.113 ms/op
                 createUser·p0.9999: 18.077 ms/op
                 createUser·p1.00:   20.808 ms/op

Iteration   3: 3.856 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.897 ms/op
                 createUser·p0.50:   3.809 ms/op
                 createUser·p0.90:   4.620 ms/op
                 createUser·p0.95:   4.874 ms/op
                 createUser·p0.99:   5.308 ms/op
                 createUser·p0.999:  17.533 ms/op
                 createUser·p0.9999: 32.997 ms/op
                 createUser·p1.00:   33.194 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 249778
  mean =      3.841 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5239 
    [ 2.500,  5.000) = 236538 
    [ 5.000,  7.500) = 7138 
    [ 7.500, 10.000) = 412 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 40 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.659 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      5.407 ms/op
     p(99.9000) =     12.921 ms/op
     p(99.9900) =     32.834 ms/op
     p(99.9990) =     33.112 ms/op
     p(99.9999) =     33.194 ms/op
    p(100.0000) =     33.194 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.061 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.876 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.631 ±(99.9%) 0.008 ms/op
Iteration   1: 3.571 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.944 ms/op
                 existUser·p0.50:   3.609 ms/op
                 existUser·p0.90:   4.383 ms/op
                 existUser·p0.95:   4.604 ms/op
                 existUser·p0.99:   5.161 ms/op
                 existUser·p0.999:  8.280 ms/op
                 existUser·p0.9999: 21.923 ms/op
                 existUser·p1.00:   22.348 ms/op

Iteration   2: 3.607 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.556 ms/op
                 existUser·p0.50:   3.576 ms/op
                 existUser·p0.90:   4.243 ms/op
                 existUser·p0.95:   4.530 ms/op
                 existUser·p0.99:   5.243 ms/op
                 existUser·p0.999:  10.157 ms/op
                 existUser·p0.9999: 16.571 ms/op
                 existUser·p1.00:   17.400 ms/op

Iteration   3: 3.733 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.625 ms/op
                 existUser·p0.50:   3.715 ms/op
                 existUser·p0.90:   4.579 ms/op
                 existUser·p0.95:   4.784 ms/op
                 existUser·p0.99:   5.145 ms/op
                 existUser·p0.999:  11.622 ms/op
                 existUser·p0.9999: 17.400 ms/op
                 existUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 264042
  mean =      3.636 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12054 
    [ 2.500,  5.000) = 247446 
    [ 5.000,  7.500) = 4194 
    [ 7.500, 10.000) = 99 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.556 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      5.161 ms/op
     p(99.9000) =      8.961 ms/op
     p(99.9900) =     21.319 ms/op
     p(99.9990) =     22.219 ms/op
     p(99.9999) =     22.348 ms/op
    p(100.0000) =     22.348 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.381 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.895 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.816 ±(99.9%) 0.009 ms/op
Iteration   1: 3.741 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.014 ms/op
                 getUser·p0.50:   3.727 ms/op
                 getUser·p0.90:   4.653 ms/op
                 getUser·p0.95:   4.907 ms/op
                 getUser·p0.99:   5.480 ms/op
                 getUser·p0.999:  8.710 ms/op
                 getUser·p0.9999: 17.319 ms/op
                 getUser·p1.00:   18.350 ms/op

Iteration   2: 3.735 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.689 ms/op
                 getUser·p0.50:   3.699 ms/op
                 getUser·p0.90:   4.465 ms/op
                 getUser·p0.95:   4.743 ms/op
                 getUser·p0.99:   5.358 ms/op
                 getUser·p0.999:  12.171 ms/op
                 getUser·p0.9999: 16.116 ms/op
                 getUser·p1.00:   17.236 ms/op

Iteration   3: 3.746 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.748 ms/op
                 getUser·p0.50:   3.707 ms/op
                 getUser·p0.90:   4.522 ms/op
                 getUser·p0.95:   4.776 ms/op
                 getUser·p0.99:   5.760 ms/op
                 getUser·p0.999:  8.569 ms/op
                 getUser·p0.9999: 19.694 ms/op
                 getUser·p1.00:   20.120 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 256567
  mean =      3.741 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9438 
    [ 2.500,  5.000) = 239852 
    [ 5.000,  7.500) = 6672 
    [ 7.500, 10.000) = 363 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.689 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =      9.781 ms/op
     p(99.9900) =     17.509 ms/op
     p(99.9990) =     19.951 ms/op
     p(99.9999) =     20.120 ms/op
    p(100.0000) =     20.120 ms/op


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
# Warmup Iteration   1: 6.497 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 5.093 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.888 ±(99.9%) 0.014 ms/op
Iteration   1: 4.788 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.260 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   5.718 ms/op
                 listUser·p0.95:   6.521 ms/op
                 listUser·p0.99:   8.192 ms/op
                 listUser·p0.999:  14.975 ms/op
                 listUser·p0.9999: 16.974 ms/op
                 listUser·p1.00:   17.302 ms/op

Iteration   2: 4.695 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.952 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.956 ms/op
                 listUser·p0.95:   6.578 ms/op
                 listUser·p0.99:   8.265 ms/op
                 listUser·p0.999:  15.900 ms/op
                 listUser·p0.9999: 17.812 ms/op
                 listUser·p1.00:   18.743 ms/op

Iteration   3: 4.769 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.153 ms/op
                 listUser·p0.50:   4.620 ms/op
                 listUser·p0.90:   5.726 ms/op
                 listUser·p0.95:   6.488 ms/op
                 listUser·p0.99:   8.167 ms/op
                 listUser·p0.999:  18.600 ms/op
                 listUser·p0.9999: 21.163 ms/op
                 listUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 202098
  mean =      4.750 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 372 
    [ 2.500,  5.000) = 150227 
    [ 5.000,  7.500) = 47468 
    [ 7.500, 10.000) = 3397 
    [10.000, 12.500) = 297 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 148 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.952 ms/op
     p(50.0000) =      4.596 ms/op
     p(90.0000) =      5.800 ms/op
     p(95.0000) =      6.529 ms/op
     p(99.0000) =      8.208 ms/op
     p(99.9000) =     15.909 ms/op
     p(99.9900) =     20.630 ms/op
     p(99.9990) =     21.528 ms/op
     p(99.9999) =     21.627 ms/op
    p(100.0000) =     21.627 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.560 ± 1.960  ops/ms
ClientGrpc.existUser                       thrpt       3   8.815 ± 3.464  ops/ms
ClientGrpc.getUser                         thrpt       3   8.529 ± 2.331  ops/ms
ClientGrpc.listUser                        thrpt       3   6.704 ± 1.286  ops/ms
ClientGrpc.createUser                       avgt       3   3.790 ± 1.607   ms/op
ClientGrpc.existUser                        avgt       3   3.602 ± 0.348   ms/op
ClientGrpc.getUser                          avgt       3   3.822 ± 0.579   ms/op
ClientGrpc.listUser                         avgt       3   4.729 ± 1.870   ms/op
ClientGrpc.createUser                     sample  249778   3.841 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.659           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.793           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.628           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.874           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.407           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.921           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.834           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.194           ms/op
ClientGrpc.existUser                      sample  264042   3.636 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.556           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.625           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.424           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.669           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.161           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.961           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.319           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.348           ms/op
ClientGrpc.getUser                        sample  256567   3.741 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.689           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.711           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.555           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.817           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.513           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.781           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.509           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.120           ms/op
ClientGrpc.listUser                       sample  202098   4.750 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.952           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.596           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.800           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.529           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.208           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.909           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.630           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.627           ms/op
