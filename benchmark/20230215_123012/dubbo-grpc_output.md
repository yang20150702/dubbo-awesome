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
# Warmup Iteration   1: 4.887 ops/ms
# Warmup Iteration   2: 9.537 ops/ms
# Warmup Iteration   3: 10.559 ops/ms
Iteration   1: 10.626 ops/ms
Iteration   2: 10.476 ops/ms
Iteration   3: 10.211 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.438 ±(99.9%) 3.832 ops/ms [Average]
  (min, avg, max) = (10.211, 10.438, 10.626), stdev = 0.210
  CI (99.9%): [6.605, 14.270] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.786 ops/ms
# Warmup Iteration   2: 10.706 ops/ms
# Warmup Iteration   3: 10.963 ops/ms
Iteration   1: 10.766 ops/ms
Iteration   2: 10.808 ops/ms
Iteration   3: 10.976 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.850 ±(99.9%) 2.030 ops/ms [Average]
  (min, avg, max) = (10.766, 10.850, 10.976), stdev = 0.111
  CI (99.9%): [8.820, 12.880] (assumes normal distribution)


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
# Warmup Iteration   1: 7.951 ops/ms
# Warmup Iteration   2: 10.373 ops/ms
# Warmup Iteration   3: 10.534 ops/ms
Iteration   1: 10.795 ops/ms
Iteration   2: 10.965 ops/ms
Iteration   3: 10.329 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.696 ±(99.9%) 6.013 ops/ms [Average]
  (min, avg, max) = (10.329, 10.696, 10.965), stdev = 0.330
  CI (99.9%): [4.684, 16.709] (assumes normal distribution)


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
# Warmup Iteration   1: 6.466 ops/ms
# Warmup Iteration   2: 7.912 ops/ms
# Warmup Iteration   3: 7.996 ops/ms
Iteration   1: 8.184 ops/ms
Iteration   2: 8.098 ops/ms
Iteration   3: 8.361 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.214 ±(99.9%) 2.448 ops/ms [Average]
  (min, avg, max) = (8.098, 8.214, 8.361), stdev = 0.134
  CI (99.9%): [5.767, 10.662] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.770 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.947 ±(99.9%) 0.003 ms/op
Iteration   1: 3.112 ±(99.9%) 0.002 ms/op
Iteration   2: 3.093 ±(99.9%) 0.002 ms/op
Iteration   3: 3.105 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.104 ±(99.9%) 0.176 ms/op [Average]
  (min, avg, max) = (3.093, 3.104, 3.112), stdev = 0.010
  CI (99.9%): [2.928, 3.279] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.819 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.993 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 2.855 ±(99.9%) 0.003 ms/op
Iteration   1: 2.833 ±(99.9%) 0.005 ms/op
Iteration   2: 2.963 ±(99.9%) 0.002 ms/op
Iteration   3: 2.917 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.904 ±(99.9%) 1.203 ms/op [Average]
  (min, avg, max) = (2.833, 2.904, 2.963), stdev = 0.066
  CI (99.9%): [1.701, 4.108] (assumes normal distribution)


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
# Warmup Iteration   1: 3.771 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.022 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.003 ms/op
Iteration   1: 3.088 ±(99.9%) 0.002 ms/op
Iteration   2: 3.033 ±(99.9%) 0.002 ms/op
Iteration   3: 3.047 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.056 ±(99.9%) 0.520 ms/op [Average]
  (min, avg, max) = (3.033, 3.056, 3.088), stdev = 0.029
  CI (99.9%): [2.536, 3.576] (assumes normal distribution)


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
# Warmup Iteration   1: 4.373 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.655 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.951 ±(99.9%) 0.014 ms/op
Iteration   1: 3.919 ±(99.9%) 0.009 ms/op
Iteration   2: 3.840 ±(99.9%) 0.010 ms/op
Iteration   3: 3.860 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.873 ±(99.9%) 0.753 ms/op [Average]
  (min, avg, max) = (3.840, 3.873, 3.919), stdev = 0.041
  CI (99.9%): [3.120, 4.626] (assumes normal distribution)


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
# Warmup Iteration   1: 3.628 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.115 ±(99.9%) 0.007 ms/op
Iteration   1: 3.091 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.541 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  6.531 ms/op
                 createUser·p0.9999: 13.899 ms/op
                 createUser·p1.00:   14.221 ms/op

Iteration   2: 3.061 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.698 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.161 ms/op
                 createUser·p0.999:  7.288 ms/op
                 createUser·p0.9999: 19.351 ms/op
                 createUser·p1.00:   19.661 ms/op

Iteration   3: 3.079 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.461 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  9.359 ms/op
                 createUser·p0.9999: 14.975 ms/op
                 createUser·p1.00:   15.778 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311937
  mean =      3.077 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 877 
    [ 1.250,  2.500) = 29012 
    [ 2.500,  3.750) = 252536 
    [ 3.750,  5.000) = 28630 
    [ 5.000,  6.250) = 358 
    [ 6.250,  7.500) = 235 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 65 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.461 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      7.332 ms/op
     p(99.9900) =     18.829 ms/op
     p(99.9990) =     19.562 ms/op
     p(99.9999) =     19.661 ms/op
    p(100.0000) =     19.661 ms/op


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
# Warmup Iteration   1: 3.552 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 2.918 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.905 ±(99.9%) 0.006 ms/op
Iteration   1: 2.920 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.716 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.580 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  6.914 ms/op
                 existUser·p0.9999: 16.810 ms/op
                 existUser·p1.00:   17.039 ms/op

Iteration   2: 2.980 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.672 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   4.141 ms/op
                 existUser·p0.999:  6.210 ms/op
                 existUser·p0.9999: 20.737 ms/op
                 existUser·p1.00:   22.282 ms/op

Iteration   3: 2.872 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.675 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.145 ms/op
                 existUser·p0.999:  6.955 ms/op
                 existUser·p0.9999: 17.203 ms/op
                 existUser·p1.00:   18.121 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328088
  mean =      2.923 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 58369 
    [ 2.500,  5.000) = 268912 
    [ 5.000,  7.500) = 581 
    [ 7.500, 10.000) = 9 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.672 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.170 ms/op
     p(99.9000) =      6.660 ms/op
     p(99.9900) =     18.390 ms/op
     p(99.9990) =     22.151 ms/op
     p(99.9999) =     22.282 ms/op
    p(100.0000) =     22.282 ms/op


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
# Warmup Iteration   1: 3.763 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.947 ±(99.9%) 0.007 ms/op
Iteration   1: 2.957 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.322 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.658 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  6.504 ms/op
                 getUser·p0.9999: 16.645 ms/op
                 getUser·p1.00:   17.138 ms/op

Iteration   2: 2.988 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.281 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.145 ms/op
                 getUser·p0.999:  6.726 ms/op
                 getUser·p0.9999: 17.049 ms/op
                 getUser·p1.00:   18.383 ms/op

Iteration   3: 3.079 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.557 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.912 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  7.621 ms/op
                 getUser·p0.9999: 19.714 ms/op
                 getUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319032
  mean =      3.007 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33549 
    [ 2.500,  5.000) = 284483 
    [ 5.000,  7.500) = 782 
    [ 7.500, 10.000) = 54 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.281 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.233 ms/op
     p(99.9000) =      6.898 ms/op
     p(99.9900) =     18.186 ms/op
     p(99.9990) =     20.107 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


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
# Warmup Iteration   1: 4.957 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.063 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.982 ±(99.9%) 0.012 ms/op
Iteration   1: 3.989 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.063 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   6.760 ms/op
                 listUser·p0.999:  12.571 ms/op
                 listUser·p0.9999: 19.496 ms/op
                 listUser·p1.00:   20.054 ms/op

Iteration   2: 4.003 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.098 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  16.227 ms/op
                 listUser·p0.9999: 22.446 ms/op
                 listUser·p1.00:   22.807 ms/op

Iteration   3: 4.004 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.850 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  12.587 ms/op
                 listUser·p0.9999: 21.037 ms/op
                 listUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239959
  mean =      3.998 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4713 
    [ 2.500,  5.000) = 202846 
    [ 5.000,  7.500) = 31365 
    [ 7.500, 10.000) = 613 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.850 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      5.210 ms/op
     p(95.0000) =      5.636 ms/op
     p(99.0000) =      6.750 ms/op
     p(99.9000) =     14.483 ms/op
     p(99.9900) =     21.824 ms/op
     p(99.9990) =     22.708 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.438 ± 3.832  ops/ms
ClientGrpc.existUser                       thrpt       3  10.850 ± 2.030  ops/ms
ClientGrpc.getUser                         thrpt       3  10.696 ± 6.013  ops/ms
ClientGrpc.listUser                        thrpt       3   8.214 ± 2.448  ops/ms
ClientGrpc.createUser                       avgt       3   3.104 ± 0.176   ms/op
ClientGrpc.existUser                        avgt       3   2.904 ± 1.203   ms/op
ClientGrpc.getUser                          avgt       3   3.056 ± 0.520   ms/op
ClientGrpc.listUser                         avgt       3   3.873 ± 0.753   ms/op
ClientGrpc.createUser                     sample  311937   3.077 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.461           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.052           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.731           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.920           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.260           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.332           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.829           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.661           ms/op
ClientGrpc.existUser                      sample  328088   2.923 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.672           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.900           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.576           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.764           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.170           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.660           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.390           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.282           ms/op
ClientGrpc.getUser                        sample  319032   3.007 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.281           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.011           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.592           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.797           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.233           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.898           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.186           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.218           ms/op
ClientGrpc.listUser                       sample  239959   3.998 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.850           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.801           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.210           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.636           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.750           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.483           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.824           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.807           ms/op
