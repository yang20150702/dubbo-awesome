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
# Warmup Iteration   1: 3.297 ops/ms
# Warmup Iteration   2: 7.042 ops/ms
# Warmup Iteration   3: 8.387 ops/ms
Iteration   1: 8.434 ops/ms
Iteration   2: 8.600 ops/ms
Iteration   3: 8.865 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.633 ±(99.9%) 3.967 ops/ms [Average]
  (min, avg, max) = (8.434, 8.633, 8.865), stdev = 0.217
  CI (99.9%): [4.666, 12.600] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 5.893 ops/ms
# Warmup Iteration   2: 8.683 ops/ms
# Warmup Iteration   3: 9.116 ops/ms
Iteration   1: 9.014 ops/ms
Iteration   2: 9.320 ops/ms
Iteration   3: 9.482 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.272 ±(99.9%) 4.336 ops/ms [Average]
  (min, avg, max) = (9.014, 9.272, 9.482), stdev = 0.238
  CI (99.9%): [4.936, 13.608] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.924 ops/ms
# Warmup Iteration   2: 8.454 ops/ms
# Warmup Iteration   3: 8.604 ops/ms
Iteration   1: 8.731 ops/ms
Iteration   2: 8.659 ops/ms
Iteration   3: 8.730 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.707 ±(99.9%) 0.749 ops/ms [Average]
  (min, avg, max) = (8.659, 8.707, 8.731), stdev = 0.041
  CI (99.9%): [7.958, 9.455] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.862 ops/ms
# Warmup Iteration   2: 6.220 ops/ms
# Warmup Iteration   3: 6.770 ops/ms
Iteration   1: 6.791 ops/ms
Iteration   2: 6.937 ops/ms
Iteration   3: 7.065 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.931 ±(99.9%) 2.502 ops/ms [Average]
  (min, avg, max) = (6.791, 6.931, 7.065), stdev = 0.137
  CI (99.9%): [4.429, 9.434] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.201 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.874 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.737 ±(99.9%) 0.019 ms/op
Iteration   1: 3.738 ±(99.9%) 0.003 ms/op
Iteration   2: 3.563 ±(99.9%) 0.004 ms/op
Iteration   3: 3.653 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.652 ±(99.9%) 1.596 ms/op [Average]
  (min, avg, max) = (3.563, 3.652, 3.738), stdev = 0.087
  CI (99.9%): [2.056, 5.247] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.609 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.635 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.491 ±(99.9%) 0.002 ms/op
Iteration   1: 3.552 ±(99.9%) 0.004 ms/op
Iteration   2: 3.454 ±(99.9%) 0.002 ms/op
Iteration   3: 3.558 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.521 ±(99.9%) 1.065 ms/op [Average]
  (min, avg, max) = (3.454, 3.521, 3.558), stdev = 0.058
  CI (99.9%): [2.456, 4.586] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.189 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.731 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.675 ±(99.9%) 0.004 ms/op
Iteration   1: 3.647 ±(99.9%) 0.005 ms/op
Iteration   2: 3.591 ±(99.9%) 0.005 ms/op
Iteration   3: 3.700 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.646 ±(99.9%) 0.997 ms/op [Average]
  (min, avg, max) = (3.591, 3.646, 3.700), stdev = 0.055
  CI (99.9%): [2.649, 4.643] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.677 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.967 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.682 ±(99.9%) 0.012 ms/op
Iteration   1: 4.606 ±(99.9%) 0.009 ms/op
Iteration   2: 4.717 ±(99.9%) 0.014 ms/op
Iteration   3: 4.597 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.640 ±(99.9%) 1.215 ms/op [Average]
  (min, avg, max) = (4.597, 4.640, 4.717), stdev = 0.067
  CI (99.9%): [3.424, 5.855] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.194 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.899 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.718 ±(99.9%) 0.009 ms/op
Iteration   1: 3.739 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.043 ms/op
                 createUser·p0.50:   3.674 ms/op
                 createUser·p0.90:   4.383 ms/op
                 createUser·p0.95:   4.612 ms/op
                 createUser·p0.99:   5.587 ms/op
                 createUser·p0.999:  9.117 ms/op
                 createUser·p0.9999: 14.931 ms/op
                 createUser·p1.00:   15.335 ms/op

Iteration   2: 3.747 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.120 ms/op
                 createUser·p0.50:   3.686 ms/op
                 createUser·p0.90:   4.473 ms/op
                 createUser·p0.95:   4.702 ms/op
                 createUser·p0.99:   5.267 ms/op
                 createUser·p0.999:  9.498 ms/op
                 createUser·p0.9999: 16.792 ms/op
                 createUser·p1.00:   17.203 ms/op

Iteration   3: 3.677 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.973 ms/op
                 createUser·p0.50:   3.617 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   4.588 ms/op
                 createUser·p0.99:   6.060 ms/op
                 createUser·p0.999:  13.349 ms/op
                 createUser·p0.9999: 22.807 ms/op
                 createUser·p1.00:   23.167 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 258135
  mean =      3.721 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3510 
    [ 2.500,  5.000) = 249645 
    [ 5.000,  7.500) = 4225 
    [ 7.500, 10.000) = 482 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.973 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =     10.414 ms/op
     p(99.9900) =     22.544 ms/op
     p(99.9990) =     22.932 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.034 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.619 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.573 ±(99.9%) 0.007 ms/op
Iteration   1: 3.583 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.873 ms/op
                 existUser·p0.50:   3.527 ms/op
                 existUser·p0.90:   4.350 ms/op
                 existUser·p0.95:   4.612 ms/op
                 existUser·p0.99:   5.489 ms/op
                 existUser·p0.999:  8.925 ms/op
                 existUser·p0.9999: 13.571 ms/op
                 existUser·p1.00:   14.107 ms/op

Iteration   2: 3.529 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.094 ms/op
                 existUser·p0.50:   3.453 ms/op
                 existUser·p0.90:   4.067 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   5.259 ms/op
                 existUser·p0.999:  10.531 ms/op
                 existUser·p0.9999: 15.251 ms/op
                 existUser·p1.00:   15.630 ms/op

Iteration   3: 3.535 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.955 ms/op
                 existUser·p0.50:   3.469 ms/op
                 existUser·p0.90:   4.153 ms/op
                 existUser·p0.95:   4.415 ms/op
                 existUser·p0.99:   5.120 ms/op
                 existUser·p0.999:  12.321 ms/op
                 existUser·p0.9999: 19.331 ms/op
                 existUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 270479
  mean =      3.549 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 201 
    [ 1.250,  2.500) = 4886 
    [ 2.500,  3.750) = 191146 
    [ 3.750,  5.000) = 70506 
    [ 5.000,  6.250) = 2373 
    [ 6.250,  7.500) = 637 
    [ 7.500,  8.750) = 350 
    [ 8.750, 10.000) = 101 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 98 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.873 ms/op
     p(50.0000) =      3.482 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      5.308 ms/op
     p(99.9000) =     10.257 ms/op
     p(99.9900) =     17.333 ms/op
     p(99.9990) =     19.746 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


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
# Warmup Iteration   1: 5.160 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.865 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.693 ±(99.9%) 0.008 ms/op
Iteration   1: 3.744 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.000 ms/op
                 getUser·p0.50:   3.670 ms/op
                 getUser·p0.90:   4.456 ms/op
                 getUser·p0.95:   4.710 ms/op
                 getUser·p0.99:   5.669 ms/op
                 getUser·p0.999:  8.513 ms/op
                 getUser·p0.9999: 15.652 ms/op
                 getUser·p1.00:   16.908 ms/op

Iteration   2: 3.725 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.165 ms/op
                 getUser·p0.50:   3.658 ms/op
                 getUser·p0.90:   4.342 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   5.612 ms/op
                 getUser·p0.999:  8.657 ms/op
                 getUser·p0.9999: 17.433 ms/op
                 getUser·p1.00:   17.662 ms/op

Iteration   3: 3.654 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.854 ms/op
                 getUser·p0.50:   3.596 ms/op
                 getUser·p0.90:   4.235 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   5.538 ms/op
                 getUser·p0.999:  9.986 ms/op
                 getUser·p0.9999: 19.472 ms/op
                 getUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 258730
  mean =      3.707 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 18 
    [ 1.250,  2.500) = 3257 
    [ 2.500,  3.750) = 149969 
    [ 3.750,  5.000) = 100275 
    [ 5.000,  6.250) = 3798 
    [ 6.250,  7.500) = 793 
    [ 7.500,  8.750) = 367 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 46 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.854 ms/op
     p(50.0000) =      3.641 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =      8.704 ms/op
     p(99.9900) =     19.075 ms/op
     p(99.9990) =     19.871 ms/op
     p(99.9999) =     19.956 ms/op
    p(100.0000) =     19.956 ms/op


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
# Warmup Iteration   1: 6.564 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.964 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.709 ±(99.9%) 0.014 ms/op
Iteration   1: 4.812 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.055 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   5.767 ms/op
                 listUser·p0.95:   6.701 ms/op
                 listUser·p0.99:   8.266 ms/op
                 listUser·p0.999:  24.306 ms/op
                 listUser·p0.9999: 27.525 ms/op
                 listUser·p1.00:   29.786 ms/op

Iteration   2: 4.669 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.399 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.579 ms/op
                 listUser·p0.95:   6.250 ms/op
                 listUser·p0.99:   7.954 ms/op
                 listUser·p0.999:  23.495 ms/op
                 listUser·p0.9999: 25.756 ms/op
                 listUser·p1.00:   27.918 ms/op

Iteration   3: 4.700 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.999 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   6.128 ms/op
                 listUser·p0.99:   8.339 ms/op
                 listUser·p0.999:  17.563 ms/op
                 listUser·p0.9999: 21.390 ms/op
                 listUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 202971
  mean =      4.726 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 313 
    [ 2.500,  5.000) = 159313 
    [ 5.000,  7.500) = 39040 
    [ 7.500, 10.000) = 3568 
    [10.000, 12.500) = 350 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 77 

  Percentiles, ms/op:
      p(0.0000) =      0.999 ms/op
     p(50.0000) =      4.579 ms/op
     p(90.0000) =      5.546 ms/op
     p(95.0000) =      6.365 ms/op
     p(99.0000) =      8.192 ms/op
     p(99.9000) =     21.137 ms/op
     p(99.9900) =     26.916 ms/op
     p(99.9990) =     28.112 ms/op
     p(99.9999) =     29.786 ms/op
    p(100.0000) =     29.786 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.633 ± 3.967  ops/ms
ClientGrpc.existUser                       thrpt       3   9.272 ± 4.336  ops/ms
ClientGrpc.getUser                         thrpt       3   8.707 ± 0.749  ops/ms
ClientGrpc.listUser                        thrpt       3   6.931 ± 2.502  ops/ms
ClientGrpc.createUser                       avgt       3   3.652 ± 1.596   ms/op
ClientGrpc.existUser                        avgt       3   3.521 ± 1.065   ms/op
ClientGrpc.getUser                          avgt       3   3.646 ± 0.997   ms/op
ClientGrpc.listUser                         avgt       3   4.640 ± 1.215   ms/op
ClientGrpc.createUser                     sample  258135   3.721 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.973           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.658           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.399           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.645           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.612           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.414           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.544           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.167           ms/op
ClientGrpc.existUser                      sample  270479   3.549 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.873           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.482           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.481           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.308           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.257           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.333           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.890           ms/op
ClientGrpc.getUser                        sample  258730   3.707 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.854           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.641           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.350           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.620           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.612           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.704           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.075           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.956           ms/op
ClientGrpc.listUser                       sample  202971   4.726 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.999           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.579           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.546           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.365           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.192           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.137           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.916           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.786           ms/op
