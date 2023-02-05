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
# Warmup Iteration   1: 4.266 ops/ms
# Warmup Iteration   2: 9.191 ops/ms
# Warmup Iteration   3: 10.104 ops/ms
Iteration   1: 10.199 ops/ms
Iteration   2: 10.230 ops/ms
Iteration   3: 9.971 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.133 ±(99.9%) 2.574 ops/ms [Average]
  (min, avg, max) = (9.971, 10.133, 10.230), stdev = 0.141
  CI (99.9%): [7.559, 12.707] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.081 ops/ms
# Warmup Iteration   2: 10.287 ops/ms
# Warmup Iteration   3: 10.645 ops/ms
Iteration   1: 10.837 ops/ms
Iteration   2: 10.604 ops/ms
Iteration   3: 10.537 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.659 ±(99.9%) 2.879 ops/ms [Average]
  (min, avg, max) = (10.537, 10.659, 10.837), stdev = 0.158
  CI (99.9%): [7.780, 13.539] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.247 ops/ms
# Warmup Iteration   2: 9.866 ops/ms
# Warmup Iteration   3: 10.138 ops/ms
Iteration   1: 10.444 ops/ms
Iteration   2: 10.350 ops/ms
Iteration   3: 10.330 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.375 ±(99.9%) 1.108 ops/ms [Average]
  (min, avg, max) = (10.330, 10.375, 10.444), stdev = 0.061
  CI (99.9%): [9.267, 11.483] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.770 ops/ms
# Warmup Iteration   2: 7.701 ops/ms
# Warmup Iteration   3: 7.902 ops/ms
Iteration   1: 8.188 ops/ms
Iteration   2: 7.798 ops/ms
Iteration   3: 8.037 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.008 ±(99.9%) 3.591 ops/ms [Average]
  (min, avg, max) = (7.798, 8.008, 8.188), stdev = 0.197
  CI (99.9%): [4.416, 11.599] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.157 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.172 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.010 ms/op
Iteration   1: 3.176 ±(99.9%) 0.003 ms/op
Iteration   2: 3.144 ±(99.9%) 0.002 ms/op
Iteration   3: 3.144 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.155 ±(99.9%) 0.341 ms/op [Average]
  (min, avg, max) = (3.144, 3.155, 3.176), stdev = 0.019
  CI (99.9%): [2.814, 3.496] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.989 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.025 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.961 ±(99.9%) 0.004 ms/op
Iteration   1: 3.091 ±(99.9%) 0.001 ms/op
Iteration   2: 3.065 ±(99.9%) 0.002 ms/op
Iteration   3: 3.000 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.052 ±(99.9%) 0.853 ms/op [Average]
  (min, avg, max) = (3.000, 3.052, 3.091), stdev = 0.047
  CI (99.9%): [2.198, 3.905] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.229 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.151 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.195 ±(99.9%) 0.002 ms/op
Iteration   1: 3.106 ±(99.9%) 0.002 ms/op
Iteration   2: 3.102 ±(99.9%) 0.001 ms/op
Iteration   3: 3.068 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.092 ±(99.9%) 0.385 ms/op [Average]
  (min, avg, max) = (3.068, 3.092, 3.106), stdev = 0.021
  CI (99.9%): [2.707, 3.476] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.007 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.080 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.955 ±(99.9%) 0.013 ms/op
Iteration   1: 3.992 ±(99.9%) 0.013 ms/op
Iteration   2: 3.940 ±(99.9%) 0.027 ms/op
Iteration   3: 3.957 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.963 ±(99.9%) 0.485 ms/op [Average]
  (min, avg, max) = (3.940, 3.963, 3.992), stdev = 0.027
  CI (99.9%): [3.478, 4.448] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.336 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.278 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.007 ms/op
Iteration   1: 3.089 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.891 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   4.645 ms/op
                 createUser·p0.999:  7.422 ms/op
                 createUser·p0.9999: 15.482 ms/op
                 createUser·p1.00:   15.892 ms/op

Iteration   2: 3.158 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.755 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.830 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   4.571 ms/op
                 createUser·p0.999:  7.972 ms/op
                 createUser·p0.9999: 13.973 ms/op
                 createUser·p1.00:   14.303 ms/op

Iteration   3: 3.159 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.574 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.871 ms/op
                 createUser·p0.95:   4.100 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  9.814 ms/op
                 createUser·p0.9999: 17.396 ms/op
                 createUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306024
  mean =      3.135 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 689 
    [ 1.250,  2.500) = 23272 
    [ 2.500,  3.750) = 247137 
    [ 3.750,  5.000) = 33386 
    [ 5.000,  6.250) = 898 
    [ 6.250,  7.500) = 281 
    [ 7.500,  8.750) = 109 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 40 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.574 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =      7.807 ms/op
     p(99.9900) =     16.604 ms/op
     p(99.9990) =     17.754 ms/op
     p(99.9999) =     17.793 ms/op
    p(100.0000) =     17.793 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.719 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.125 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.129 ±(99.9%) 0.007 ms/op
Iteration   1: 3.013 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.509 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   4.166 ms/op
                 existUser·p0.999:  7.593 ms/op
                 existUser·p0.9999: 12.911 ms/op
                 existUser·p1.00:   13.304 ms/op

Iteration   2: 3.009 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.836 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   4.141 ms/op
                 existUser·p0.999:  6.194 ms/op
                 existUser·p0.9999: 13.954 ms/op
                 existUser·p1.00:   14.172 ms/op

Iteration   3: 2.951 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.760 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.781 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   4.286 ms/op
                 existUser·p0.999:  7.172 ms/op
                 existUser·p0.9999: 16.635 ms/op
                 existUser·p1.00:   17.072 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321128
  mean =      2.990 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3036 
    [ 1.250,  2.500) = 45851 
    [ 2.500,  3.750) = 246330 
    [ 3.750,  5.000) = 24993 
    [ 5.000,  6.250) = 424 
    [ 6.250,  7.500) = 218 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.509 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      7.078 ms/op
     p(99.9900) =     16.186 ms/op
     p(99.9990) =     16.894 ms/op
     p(99.9999) =     17.072 ms/op
    p(100.0000) =     17.072 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.558 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.251 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.149 ±(99.9%) 0.006 ms/op
Iteration   1: 3.144 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.720 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  7.584 ms/op
                 getUser·p0.9999: 12.738 ms/op
                 getUser·p1.00:   13.124 ms/op

Iteration   2: 3.118 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.795 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  9.878 ms/op
                 getUser·p0.9999: 14.586 ms/op
                 getUser·p1.00:   14.762 ms/op

Iteration   3: 3.041 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.784 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  6.412 ms/op
                 getUser·p0.9999: 16.294 ms/op
                 getUser·p1.00:   19.300 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309404
  mean =      3.101 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 733 
    [ 1.250,  2.500) = 26796 
    [ 2.500,  3.750) = 251248 
    [ 3.750,  5.000) = 29493 
    [ 5.000,  6.250) = 524 
    [ 6.250,  7.500) = 243 
    [ 7.500,  8.750) = 156 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 46 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.720 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      7.848 ms/op
     p(99.9900) =     15.958 ms/op
     p(99.9990) =     16.642 ms/op
     p(99.9999) =     19.300 ms/op
    p(100.0000) =     19.300 ms/op


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
# Warmup Iteration   1: 5.630 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.108 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.124 ±(99.9%) 0.012 ms/op
Iteration   1: 3.967 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.483 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  13.654 ms/op
                 listUser·p0.9999: 19.655 ms/op
                 listUser·p1.00:   20.709 ms/op

Iteration   2: 3.997 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.925 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  14.532 ms/op
                 listUser·p0.9999: 23.200 ms/op
                 listUser·p1.00:   23.822 ms/op

Iteration   3: 3.896 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.085 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.817 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   6.636 ms/op
                 listUser·p0.999:  16.623 ms/op
                 listUser·p0.9999: 23.382 ms/op
                 listUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242751
  mean =      3.953 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2793 
    [ 2.500,  5.000) = 216377 
    [ 5.000,  7.500) = 22535 
    [ 7.500, 10.000) = 632 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 171 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.925 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.973 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     14.373 ms/op
     p(99.9900) =     23.125 ms/op
     p(99.9990) =     23.822 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.133 ± 2.574  ops/ms
ClientGrpc.existUser                       thrpt       3  10.659 ± 2.879  ops/ms
ClientGrpc.getUser                         thrpt       3  10.375 ± 1.108  ops/ms
ClientGrpc.listUser                        thrpt       3   8.008 ± 3.591  ops/ms
ClientGrpc.createUser                       avgt       3   3.155 ± 0.341   ms/op
ClientGrpc.existUser                        avgt       3   3.052 ± 0.853   ms/op
ClientGrpc.getUser                          avgt       3   3.092 ± 0.385   ms/op
ClientGrpc.listUser                         avgt       3   3.963 ± 0.485   ms/op
ClientGrpc.createUser                     sample  306024   3.135 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.574           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.092           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.805           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.055           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.555           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.807           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.604           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.793           ms/op
ClientGrpc.existUser                      sample  321128   2.990 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.509           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.998           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.686           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.867           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.078           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.186           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.072           ms/op
ClientGrpc.getUser                        sample  309404   3.101 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.720           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.072           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.748           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.944           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.366           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.848           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.958           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.300           ms/op
ClientGrpc.listUser                       sample  242751   3.953 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.925           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.797           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.973           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.669           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.734           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.373           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.125           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.921           ms/op
