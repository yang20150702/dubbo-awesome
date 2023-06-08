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
# Warmup Iteration   1: 3.226 ops/ms
# Warmup Iteration   2: 7.314 ops/ms
# Warmup Iteration   3: 8.435 ops/ms
Iteration   1: 8.793 ops/ms
Iteration   2: 8.896 ops/ms
Iteration   3: 8.669 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.786 ±(99.9%) 2.072 ops/ms [Average]
  (min, avg, max) = (8.669, 8.786, 8.896), stdev = 0.114
  CI (99.9%): [6.714, 10.858] (assumes normal distribution)


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
# Warmup Iteration   1: 6.111 ops/ms
# Warmup Iteration   2: 8.296 ops/ms
# Warmup Iteration   3: 9.011 ops/ms
Iteration   1: 9.194 ops/ms
Iteration   2: 9.307 ops/ms
Iteration   3: 9.162 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.221 ±(99.9%) 1.386 ops/ms [Average]
  (min, avg, max) = (9.162, 9.221, 9.307), stdev = 0.076
  CI (99.9%): [7.834, 10.607] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.527 ops/ms
# Warmup Iteration   2: 7.961 ops/ms
# Warmup Iteration   3: 8.505 ops/ms
Iteration   1: 8.593 ops/ms
Iteration   2: 8.684 ops/ms
Iteration   3: 8.693 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.657 ±(99.9%) 1.016 ops/ms [Average]
  (min, avg, max) = (8.593, 8.657, 8.693), stdev = 0.056
  CI (99.9%): [7.641, 9.673] (assumes normal distribution)


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
# Warmup Iteration   1: 4.234 ops/ms
# Warmup Iteration   2: 6.250 ops/ms
# Warmup Iteration   3: 6.632 ops/ms
Iteration   1: 6.627 ops/ms
Iteration   2: 6.780 ops/ms
Iteration   3: 6.710 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.706 ±(99.9%) 1.395 ops/ms [Average]
  (min, avg, max) = (6.627, 6.706, 6.780), stdev = 0.076
  CI (99.9%): [5.311, 8.100] (assumes normal distribution)


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
# Warmup Iteration   1: 5.319 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.865 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.755 ±(99.9%) 0.004 ms/op
Iteration   1: 3.632 ±(99.9%) 0.003 ms/op
Iteration   2: 3.627 ±(99.9%) 0.002 ms/op
Iteration   3: 3.629 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.629 ±(99.9%) 0.044 ms/op [Average]
  (min, avg, max) = (3.627, 3.629, 3.632), stdev = 0.002
  CI (99.9%): [3.586, 3.673] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.158 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.659 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.461 ±(99.9%) 0.006 ms/op
Iteration   1: 3.480 ±(99.9%) 0.003 ms/op
Iteration   2: 3.467 ±(99.9%) 0.004 ms/op
Iteration   3: 3.503 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.483 ±(99.9%) 0.332 ms/op [Average]
  (min, avg, max) = (3.467, 3.483, 3.503), stdev = 0.018
  CI (99.9%): [3.151, 3.816] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.532 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.013 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.701 ±(99.9%) 0.011 ms/op
Iteration   1: 3.588 ±(99.9%) 0.004 ms/op
Iteration   2: 3.657 ±(99.9%) 0.003 ms/op
Iteration   3: 3.694 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.646 ±(99.9%) 0.982 ms/op [Average]
  (min, avg, max) = (3.588, 3.646, 3.694), stdev = 0.054
  CI (99.9%): [2.664, 4.628] (assumes normal distribution)


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
# Warmup Iteration   1: 6.368 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 5.135 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.744 ±(99.9%) 0.015 ms/op
Iteration   1: 4.855 ±(99.9%) 0.021 ms/op
Iteration   2: 4.695 ±(99.9%) 0.013 ms/op
Iteration   3: 4.776 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.775 ±(99.9%) 1.459 ms/op [Average]
  (min, avg, max) = (4.695, 4.775, 4.855), stdev = 0.080
  CI (99.9%): [3.317, 6.234] (assumes normal distribution)


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
# Warmup Iteration   1: 5.500 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 3.909 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.605 ±(99.9%) 0.008 ms/op
Iteration   1: 3.699 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.672 ms/op
                 createUser·p0.50:   3.633 ms/op
                 createUser·p0.90:   4.473 ms/op
                 createUser·p0.95:   4.760 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  13.225 ms/op
                 createUser·p0.9999: 15.368 ms/op
                 createUser·p1.00:   15.647 ms/op

Iteration   2: 3.731 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.085 ms/op
                 createUser·p0.50:   3.670 ms/op
                 createUser·p0.90:   4.448 ms/op
                 createUser·p0.95:   4.702 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  8.508 ms/op
                 createUser·p0.9999: 28.830 ms/op
                 createUser·p1.00:   30.966 ms/op

Iteration   3: 3.675 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.991 ms/op
                 createUser·p0.50:   3.604 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   4.615 ms/op
                 createUser·p0.99:   5.530 ms/op
                 createUser·p0.999:  8.380 ms/op
                 createUser·p0.9999: 40.849 ms/op
                 createUser·p1.00:   42.009 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 259292
  mean =      3.702 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 252937 
    [ 5.000, 10.000) = 6076 
    [10.000, 15.000) = 175 
    [15.000, 20.000) = 27 
    [20.000, 25.000) = 14 
    [25.000, 30.000) = 28 
    [30.000, 35.000) = 4 
    [35.000, 40.000) = 8 
    [40.000, 45.000) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.672 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =     10.820 ms/op
     p(99.9900) =     39.911 ms/op
     p(99.9990) =     41.341 ms/op
     p(99.9999) =     42.009 ms/op
    p(100.0000) =     42.009 ms/op


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
# Warmup Iteration   1: 5.099 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.671 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.646 ±(99.9%) 0.007 ms/op
Iteration   1: 3.509 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.716 ms/op
                 existUser·p0.50:   3.461 ms/op
                 existUser·p0.90:   4.194 ms/op
                 existUser·p0.95:   4.473 ms/op
                 existUser·p0.99:   5.516 ms/op
                 existUser·p0.999:  12.083 ms/op
                 existUser·p0.9999: 18.441 ms/op
                 existUser·p1.00:   18.907 ms/op

Iteration   2: 3.512 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.852 ms/op
                 existUser·p0.50:   3.445 ms/op
                 existUser·p0.90:   4.112 ms/op
                 existUser·p0.95:   4.440 ms/op
                 existUser·p0.99:   5.497 ms/op
                 existUser·p0.999:  8.552 ms/op
                 existUser·p0.9999: 16.474 ms/op
                 existUser·p1.00:   16.908 ms/op

Iteration   3: 3.522 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.655 ms/op
                 existUser·p0.50:   3.457 ms/op
                 existUser·p0.90:   4.104 ms/op
                 existUser·p0.95:   4.448 ms/op
                 existUser·p0.99:   5.686 ms/op
                 existUser·p0.999:  11.148 ms/op
                 existUser·p0.9999: 20.117 ms/op
                 existUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 273007
  mean =      3.514 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7454 
    [ 2.500,  5.000) = 260359 
    [ 5.000,  7.500) = 4435 
    [ 7.500, 10.000) = 442 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.655 ms/op
     p(50.0000) =      3.453 ms/op
     p(90.0000) =      4.141 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =     10.519 ms/op
     p(99.9900) =     19.127 ms/op
     p(99.9990) =     20.432 ms/op
     p(99.9999) =     20.578 ms/op
    p(100.0000) =     20.578 ms/op


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
# Warmup Iteration   1: 5.140 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.965 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.709 ±(99.9%) 0.010 ms/op
Iteration   1: 3.696 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.037 ms/op
                 getUser·p0.50:   3.629 ms/op
                 getUser·p0.90:   4.407 ms/op
                 getUser·p0.95:   4.719 ms/op
                 getUser·p0.99:   5.827 ms/op
                 getUser·p0.999:  10.912 ms/op
                 getUser·p0.9999: 14.517 ms/op
                 getUser·p1.00:   14.729 ms/op

Iteration   2: 3.643 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.959 ms/op
                 getUser·p0.50:   3.596 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   4.743 ms/op
                 getUser·p0.99:   5.759 ms/op
                 getUser·p0.999:  8.426 ms/op
                 getUser·p0.9999: 22.748 ms/op
                 getUser·p1.00:   23.069 ms/op

Iteration   3: 3.670 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.905 ms/op
                 getUser·p0.50:   3.609 ms/op
                 getUser·p0.90:   4.383 ms/op
                 getUser·p0.95:   4.719 ms/op
                 getUser·p0.99:   5.792 ms/op
                 getUser·p0.999:  11.890 ms/op
                 getUser·p0.9999: 18.800 ms/op
                 getUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 261702
  mean =      3.670 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8613 
    [ 2.500,  5.000) = 245255 
    [ 5.000,  7.500) = 7077 
    [ 7.500, 10.000) = 447 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.905 ms/op
     p(50.0000) =      3.613 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =     11.474 ms/op
     p(99.9900) =     22.167 ms/op
     p(99.9990) =     22.963 ms/op
     p(99.9999) =     23.069 ms/op
    p(100.0000) =     23.069 ms/op


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
# Warmup Iteration   1: 6.319 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 5.214 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.958 ±(99.9%) 0.016 ms/op
Iteration   1: 4.847 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.343 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   6.070 ms/op
                 listUser·p0.95:   6.955 ms/op
                 listUser·p0.99:   8.471 ms/op
                 listUser·p0.999:  16.171 ms/op
                 listUser·p0.9999: 26.870 ms/op
                 listUser·p1.00:   27.066 ms/op

Iteration   2: 4.985 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.343 ms/op
                 listUser·p0.50:   4.653 ms/op
                 listUser·p0.90:   6.636 ms/op
                 listUser·p0.95:   7.594 ms/op
                 listUser·p0.99:   9.830 ms/op
                 listUser·p0.999:  18.343 ms/op
                 listUser·p0.9999: 22.757 ms/op
                 listUser·p1.00:   24.314 ms/op

Iteration   3: 4.783 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.122 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   6.259 ms/op
                 listUser·p0.95:   6.963 ms/op
                 listUser·p0.99:   8.684 ms/op
                 listUser·p0.999:  19.923 ms/op
                 listUser·p0.9999: 23.111 ms/op
                 listUser·p1.00:   24.642 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 197187
  mean =      4.870 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 356 
    [ 2.500,  5.000) = 138674 
    [ 5.000,  7.500) = 50717 
    [ 7.500, 10.000) = 6408 
    [10.000, 12.500) = 618 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.122 ms/op
     p(50.0000) =      4.596 ms/op
     p(90.0000) =      6.332 ms/op
     p(95.0000) =      7.176 ms/op
     p(99.0000) =      8.962 ms/op
     p(99.9000) =     19.202 ms/op
     p(99.9900) =     26.308 ms/op
     p(99.9990) =     27.035 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.786 ± 2.072  ops/ms
ClientGrpc.existUser                       thrpt       3   9.221 ± 1.386  ops/ms
ClientGrpc.getUser                         thrpt       3   8.657 ± 1.016  ops/ms
ClientGrpc.listUser                        thrpt       3   6.706 ± 1.395  ops/ms
ClientGrpc.createUser                       avgt       3   3.629 ± 0.044   ms/op
ClientGrpc.existUser                        avgt       3   3.483 ± 0.332   ms/op
ClientGrpc.getUser                          avgt       3   3.646 ± 0.982   ms/op
ClientGrpc.listUser                         avgt       3   4.775 ± 1.459   ms/op
ClientGrpc.createUser                     sample  259292   3.702 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.672           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.637           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.694           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.571           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.820           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          39.911           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          42.009           ms/op
ClientGrpc.existUser                      sample  273007   3.514 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.655           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.453           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.141           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.456           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.562           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.519           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.127           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.578           ms/op
ClientGrpc.getUser                        sample  261702   3.670 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.905           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.613           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.391           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.727           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.784           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.474           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.167           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.069           ms/op
ClientGrpc.listUser                       sample  197187   4.870 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.122           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.596           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.332           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.176           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.962           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.202           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.308           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.066           ms/op
