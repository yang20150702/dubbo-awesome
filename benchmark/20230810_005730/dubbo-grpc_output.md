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
# Warmup Iteration   1: 3.249 ops/ms
# Warmup Iteration   2: 6.553 ops/ms
# Warmup Iteration   3: 8.133 ops/ms
Iteration   1: 8.592 ops/ms
Iteration   2: 8.666 ops/ms
Iteration   3: 8.381 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.546 ±(99.9%) 2.693 ops/ms [Average]
  (min, avg, max) = (8.381, 8.546, 8.666), stdev = 0.148
  CI (99.9%): [5.854, 11.239] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.798 ops/ms
# Warmup Iteration   2: 8.606 ops/ms
# Warmup Iteration   3: 9.158 ops/ms
Iteration   1: 9.397 ops/ms
Iteration   2: 9.290 ops/ms
Iteration   3: 9.160 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.282 ±(99.9%) 2.169 ops/ms [Average]
  (min, avg, max) = (9.160, 9.282, 9.397), stdev = 0.119
  CI (99.9%): [7.113, 11.452] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.317 ops/ms
# Warmup Iteration   2: 8.054 ops/ms
# Warmup Iteration   3: 8.606 ops/ms
Iteration   1: 8.574 ops/ms
Iteration   2: 8.435 ops/ms
Iteration   3: 8.511 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.507 ±(99.9%) 1.265 ops/ms [Average]
  (min, avg, max) = (8.435, 8.507, 8.574), stdev = 0.069
  CI (99.9%): [7.241, 9.772] (assumes normal distribution)


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
# Warmup Iteration   1: 4.272 ops/ms
# Warmup Iteration   2: 6.022 ops/ms
# Warmup Iteration   3: 6.494 ops/ms
Iteration   1: 6.767 ops/ms
Iteration   2: 6.657 ops/ms
Iteration   3: 6.651 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.691 ±(99.9%) 1.188 ops/ms [Average]
  (min, avg, max) = (6.651, 6.691, 6.767), stdev = 0.065
  CI (99.9%): [5.503, 7.880] (assumes normal distribution)


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
# Warmup Iteration   1: 5.468 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.905 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.832 ±(99.9%) 0.009 ms/op
Iteration   1: 3.678 ±(99.9%) 0.005 ms/op
Iteration   2: 3.586 ±(99.9%) 0.005 ms/op
Iteration   3: 3.617 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.627 ±(99.9%) 0.857 ms/op [Average]
  (min, avg, max) = (3.586, 3.627, 3.678), stdev = 0.047
  CI (99.9%): [2.770, 4.484] (assumes normal distribution)


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
# Warmup Iteration   1: 4.973 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.705 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.489 ±(99.9%) 0.004 ms/op
Iteration   1: 3.490 ±(99.9%) 0.003 ms/op
Iteration   2: 3.573 ±(99.9%) 0.004 ms/op
Iteration   3: 3.526 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.529 ±(99.9%) 0.761 ms/op [Average]
  (min, avg, max) = (3.490, 3.529, 3.573), stdev = 0.042
  CI (99.9%): [2.769, 4.290] (assumes normal distribution)


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
# Warmup Iteration   1: 5.050 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.967 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.684 ±(99.9%) 0.004 ms/op
Iteration   1: 3.718 ±(99.9%) 0.005 ms/op
Iteration   2: 3.675 ±(99.9%) 0.003 ms/op
Iteration   3: 3.656 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.683 ±(99.9%) 0.584 ms/op [Average]
  (min, avg, max) = (3.656, 3.683, 3.718), stdev = 0.032
  CI (99.9%): [3.099, 4.267] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.437 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 5.003 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.891 ±(99.9%) 0.016 ms/op
Iteration   1: 4.856 ±(99.9%) 0.009 ms/op
Iteration   2: 4.957 ±(99.9%) 0.013 ms/op
Iteration   3: 4.873 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.895 ±(99.9%) 0.982 ms/op [Average]
  (min, avg, max) = (4.856, 4.895, 4.957), stdev = 0.054
  CI (99.9%): [3.913, 5.878] (assumes normal distribution)


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
# Warmup Iteration   1: 5.355 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.981 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.880 ±(99.9%) 0.012 ms/op
Iteration   1: 3.743 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.809 ms/op
                 createUser·p0.50:   3.670 ms/op
                 createUser·p0.90:   4.579 ms/op
                 createUser·p0.95:   4.997 ms/op
                 createUser·p0.99:   6.610 ms/op
                 createUser·p0.999:  10.452 ms/op
                 createUser·p0.9999: 16.175 ms/op
                 createUser·p1.00:   16.810 ms/op

Iteration   2: 3.713 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.104 ms/op
                 createUser·p0.50:   3.609 ms/op
                 createUser·p0.90:   4.465 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   6.562 ms/op
                 createUser·p0.999:  9.826 ms/op
                 createUser·p0.9999: 28.684 ms/op
                 createUser·p1.00:   28.967 ms/op

Iteration   3: 3.728 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.736 ms/op
                 createUser·p0.50:   3.641 ms/op
                 createUser·p0.90:   4.456 ms/op
                 createUser·p0.95:   4.792 ms/op
                 createUser·p0.99:   6.390 ms/op
                 createUser·p0.999:  18.785 ms/op
                 createUser·p0.9999: 23.999 ms/op
                 createUser·p1.00:   24.314 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 257714
  mean =      3.728 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8508 
    [ 2.500,  5.000) = 237834 
    [ 5.000,  7.500) = 10010 
    [ 7.500, 10.000) = 1007 
    [10.000, 12.500) = 157 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      6.529 ms/op
     p(99.9000) =     11.150 ms/op
     p(99.9900) =     27.671 ms/op
     p(99.9990) =     28.896 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


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
# Warmup Iteration   1: 4.771 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.926 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.697 ±(99.9%) 0.014 ms/op
Iteration   1: 3.591 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.005 ms/op
                 existUser·p0.50:   3.494 ms/op
                 existUser·p0.90:   4.358 ms/op
                 existUser·p0.95:   4.891 ms/op
                 existUser·p0.99:   7.053 ms/op
                 existUser·p0.999:  12.009 ms/op
                 existUser·p0.9999: 17.373 ms/op
                 existUser·p1.00:   17.564 ms/op

Iteration   2: 3.654 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.934 ms/op
                 existUser·p0.50:   3.523 ms/op
                 existUser·p0.90:   4.456 ms/op
                 existUser·p0.95:   4.932 ms/op
                 existUser·p0.99:   6.808 ms/op
                 existUser·p0.999:  11.076 ms/op
                 existUser·p0.9999: 31.490 ms/op
                 existUser·p1.00:   31.654 ms/op

Iteration   3: 3.568 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.848 ms/op
                 existUser·p0.50:   3.506 ms/op
                 existUser·p0.90:   4.391 ms/op
                 existUser·p0.95:   4.833 ms/op
                 existUser·p0.99:   6.291 ms/op
                 existUser·p0.999:  9.836 ms/op
                 existUser·p0.9999: 24.675 ms/op
                 existUser·p1.00:   25.395 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 266315
  mean =      3.604 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13335 
    [ 2.500,  5.000) = 241583 
    [ 5.000,  7.500) = 9764 
    [ 7.500, 10.000) = 1257 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.848 ms/op
     p(50.0000) =      3.506 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      6.742 ms/op
     p(99.9000) =     10.956 ms/op
     p(99.9900) =     29.393 ms/op
     p(99.9990) =     31.599 ms/op
     p(99.9999) =     31.654 ms/op
    p(100.0000) =     31.654 ms/op


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
# Warmup Iteration   1: 5.471 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.998 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.951 ±(99.9%) 0.012 ms/op
Iteration   1: 3.725 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.853 ms/op
                 getUser·p0.50:   3.633 ms/op
                 getUser·p0.90:   4.497 ms/op
                 getUser·p0.95:   4.874 ms/op
                 getUser·p0.99:   6.206 ms/op
                 getUser·p0.999:  9.847 ms/op
                 getUser·p0.9999: 14.975 ms/op
                 getUser·p1.00:   15.647 ms/op

Iteration   2: 3.789 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.756 ms/op
                 getUser·p0.50:   3.686 ms/op
                 getUser·p0.90:   4.620 ms/op
                 getUser·p0.95:   5.071 ms/op
                 getUser·p0.99:   6.504 ms/op
                 getUser·p0.999:  10.892 ms/op
                 getUser·p0.9999: 26.823 ms/op
                 getUser·p1.00:   27.951 ms/op

Iteration   3: 3.804 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.738 ms/op
                 getUser·p0.50:   3.703 ms/op
                 getUser·p0.90:   4.620 ms/op
                 getUser·p0.95:   5.112 ms/op
                 getUser·p0.99:   7.422 ms/op
                 getUser·p0.999:  10.304 ms/op
                 getUser·p0.9999: 18.416 ms/op
                 getUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 254457
  mean =      3.772 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8590 
    [ 2.500,  5.000) = 232936 
    [ 5.000,  7.500) = 11256 
    [ 7.500, 10.000) = 1365 
    [10.000, 12.500) = 180 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.738 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      5.014 ms/op
     p(99.0000) =      6.693 ms/op
     p(99.9000) =     10.322 ms/op
     p(99.9900) =     25.938 ms/op
     p(99.9990) =     27.900 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


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
# Warmup Iteration   1: 7.497 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 5.532 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.984 ±(99.9%) 0.017 ms/op
Iteration   1: 4.938 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.348 ms/op
                 listUser·p0.50:   4.678 ms/op
                 listUser·p0.90:   6.455 ms/op
                 listUser·p0.95:   7.299 ms/op
                 listUser·p0.99:   9.273 ms/op
                 listUser·p0.999:  15.162 ms/op
                 listUser·p0.9999: 17.222 ms/op
                 listUser·p1.00:   18.153 ms/op

Iteration   2: 4.925 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.204 ms/op
                 listUser·p0.50:   4.661 ms/op
                 listUser·p0.90:   6.332 ms/op
                 listUser·p0.95:   7.340 ms/op
                 listUser·p0.99:   9.224 ms/op
                 listUser·p0.999:  17.105 ms/op
                 listUser·p0.9999: 25.690 ms/op
                 listUser·p1.00:   26.280 ms/op

Iteration   3: 4.941 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   0.457 ms/op
                 listUser·p0.50:   4.694 ms/op
                 listUser·p0.90:   6.144 ms/op
                 listUser·p0.95:   7.168 ms/op
                 listUser·p0.99:   9.372 ms/op
                 listUser·p0.999:  21.168 ms/op
                 listUser·p0.9999: 30.966 ms/op
                 listUser·p1.00:   33.161 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 194522
  mean =      4.935 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 235 
    [ 2.500,  5.000) = 132518 
    [ 5.000,  7.500) = 53738 
    [ 7.500, 10.000) = 6806 
    [10.000, 12.500) = 789 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.457 ms/op
     p(50.0000) =      4.678 ms/op
     p(90.0000) =      6.332 ms/op
     p(95.0000) =      7.274 ms/op
     p(99.0000) =      9.273 ms/op
     p(99.9000) =     17.284 ms/op
     p(99.9900) =     30.867 ms/op
     p(99.9990) =     32.944 ms/op
     p(99.9999) =     33.161 ms/op
    p(100.0000) =     33.161 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.546 ± 2.693  ops/ms
ClientGrpc.existUser                       thrpt       3   9.282 ± 2.169  ops/ms
ClientGrpc.getUser                         thrpt       3   8.507 ± 1.265  ops/ms
ClientGrpc.listUser                        thrpt       3   6.691 ± 1.188  ops/ms
ClientGrpc.createUser                       avgt       3   3.627 ± 0.857   ms/op
ClientGrpc.existUser                        avgt       3   3.529 ± 0.761   ms/op
ClientGrpc.getUser                          avgt       3   3.683 ± 0.584   ms/op
ClientGrpc.listUser                         avgt       3   4.895 ± 0.982   ms/op
ClientGrpc.createUser                     sample  257714   3.728 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.736           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.637           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.497           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.915           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.529           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.150           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.671           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.967           ms/op
ClientGrpc.existUser                      sample  266315   3.604 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.848           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.506           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.399           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.882           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.742           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.956           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          29.393           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          31.654           ms/op
ClientGrpc.getUser                        sample  254457   3.772 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.738           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.674           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.579           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.014           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.693           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.322           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.938           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.951           ms/op
ClientGrpc.listUser                       sample  194522   4.935 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.457           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.678           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.332           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.274           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.273           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.284           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.867           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.161           ms/op
