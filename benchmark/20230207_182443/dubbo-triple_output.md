# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.730 ops/ms
# Warmup Iteration   2: 6.294 ops/ms
# Warmup Iteration   3: 9.250 ops/ms
Iteration   1: 9.900 ops/ms
Iteration   2: 10.282 ops/ms
Iteration   3: 10.278 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.153 ±(99.9%) 4.007 ops/ms [Average]
  (min, avg, max) = (9.900, 10.153, 10.282), stdev = 0.220
  CI (99.9%): [6.146, 14.161] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.749 ops/ms
# Warmup Iteration   2: 9.652 ops/ms
# Warmup Iteration   3: 10.224 ops/ms
Iteration   1: 10.285 ops/ms
Iteration   2: 10.741 ops/ms
Iteration   3: 9.989 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.338 ±(99.9%) 6.913 ops/ms [Average]
  (min, avg, max) = (9.989, 10.338, 10.741), stdev = 0.379
  CI (99.9%): [3.425, 17.252] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.100 ops/ms
# Warmup Iteration   2: 9.280 ops/ms
# Warmup Iteration   3: 9.732 ops/ms
Iteration   1: 9.725 ops/ms
Iteration   2: 10.288 ops/ms
Iteration   3: 10.320 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.111 ±(99.9%) 6.107 ops/ms [Average]
  (min, avg, max) = (9.725, 10.111, 10.320), stdev = 0.335
  CI (99.9%): [4.004, 16.218] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.631 ops/ms
# Warmup Iteration   2: 7.893 ops/ms
# Warmup Iteration   3: 8.191 ops/ms
Iteration   1: 8.570 ops/ms
Iteration   2: 8.387 ops/ms
Iteration   3: 8.598 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.518 ±(99.9%) 2.085 ops/ms [Average]
  (min, avg, max) = (8.387, 8.518, 8.598), stdev = 0.114
  CI (99.9%): [6.433, 10.604] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.683 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.696 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.307 ±(99.9%) 0.006 ms/op
Iteration   1: 3.231 ±(99.9%) 0.006 ms/op
Iteration   2: 3.227 ±(99.9%) 0.005 ms/op
Iteration   3: 3.192 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.217 ±(99.9%) 0.390 ms/op [Average]
  (min, avg, max) = (3.192, 3.217, 3.231), stdev = 0.021
  CI (99.9%): [2.827, 3.606] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.497 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.276 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.003 ms/op
Iteration   1: 2.994 ±(99.9%) 0.007 ms/op
Iteration   2: 2.940 ±(99.9%) 0.005 ms/op
Iteration   3: 3.052 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.995 ±(99.9%) 1.019 ms/op [Average]
  (min, avg, max) = (2.940, 2.995, 3.052), stdev = 0.056
  CI (99.9%): [1.976, 4.014] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.240 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.350 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.269 ±(99.9%) 0.004 ms/op
Iteration   1: 3.181 ±(99.9%) 0.003 ms/op
Iteration   2: 3.127 ±(99.9%) 0.001 ms/op
Iteration   3: 3.269 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.192 ±(99.9%) 1.313 ms/op [Average]
  (min, avg, max) = (3.127, 3.192, 3.269), stdev = 0.072
  CI (99.9%): [1.879, 4.505] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.393 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.186 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.779 ±(99.9%) 0.005 ms/op
Iteration   1: 3.779 ±(99.9%) 0.007 ms/op
Iteration   2: 3.739 ±(99.9%) 0.006 ms/op
Iteration   3: 3.650 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.723 ±(99.9%) 1.209 ms/op [Average]
  (min, avg, max) = (3.650, 3.723, 3.779), stdev = 0.066
  CI (99.9%): [2.514, 4.931] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.928 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.655 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.007 ms/op
Iteration   1: 3.227 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.988 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.973 ms/op
                 createUser·p0.99:   5.445 ms/op
                 createUser·p0.999:  12.748 ms/op
                 createUser·p0.9999: 20.349 ms/op
                 createUser·p1.00:   20.611 ms/op

Iteration   2: 3.096 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.182 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.404 ms/op
                 createUser·p0.95:   3.670 ms/op
                 createUser·p0.99:   5.423 ms/op
                 createUser·p0.999:  10.936 ms/op
                 createUser·p0.9999: 21.758 ms/op
                 createUser·p1.00:   23.396 ms/op

Iteration   3: 3.068 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.626 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.375 ms/op
                 createUser·p0.95:   3.555 ms/op
                 createUser·p0.99:   4.977 ms/op
                 createUser·p0.999:  15.155 ms/op
                 createUser·p0.9999: 24.084 ms/op
                 createUser·p1.00:   24.150 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 306393
  mean =      3.129 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15405 
    [ 2.500,  5.000) = 286649 
    [ 5.000,  7.500) = 3485 
    [ 7.500, 10.000) = 423 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 116 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.988 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      5.374 ms/op
     p(99.9000) =     15.100 ms/op
     p(99.9900) =     21.791 ms/op
     p(99.9990) =     24.150 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 7.254 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 3.399 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.188 ±(99.9%) 0.008 ms/op
Iteration   1: 3.129 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.118 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   5.571 ms/op
                 existUser·p0.999:  9.175 ms/op
                 existUser·p0.9999: 20.931 ms/op
                 existUser·p1.00:   21.823 ms/op

Iteration   2: 3.206 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.147 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.908 ms/op
                 existUser·p0.99:   5.956 ms/op
                 existUser·p0.999:  12.419 ms/op
                 existUser·p0.9999: 23.266 ms/op
                 existUser·p1.00:   23.626 ms/op

Iteration   3: 3.136 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.983 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   5.104 ms/op
                 existUser·p0.999:  13.074 ms/op
                 existUser·p0.9999: 26.156 ms/op
                 existUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 303904
  mean =      3.157 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22048 
    [ 2.500,  5.000) = 275928 
    [ 5.000,  7.500) = 5150 
    [ 7.500, 10.000) = 320 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.983 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =     12.435 ms/op
     p(99.9900) =     25.140 ms/op
     p(99.9990) =     26.870 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.139 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.425 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.274 ±(99.9%) 0.010 ms/op
Iteration   1: 3.151 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.389 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   5.677 ms/op
                 getUser·p0.999:  9.388 ms/op
                 getUser·p0.9999: 20.251 ms/op
                 getUser·p1.00:   21.234 ms/op

Iteration   2: 3.172 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.977 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   5.448 ms/op
                 getUser·p0.999:  9.426 ms/op
                 getUser·p0.9999: 26.900 ms/op
                 getUser·p1.00:   27.460 ms/op

Iteration   3: 3.264 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.805 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   5.669 ms/op
                 getUser·p0.999:  13.648 ms/op
                 getUser·p0.9999: 20.919 ms/op
                 getUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300478
  mean =      3.195 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7997 
    [ 2.500,  5.000) = 286553 
    [ 5.000,  7.500) = 5171 
    [ 7.500, 10.000) = 389 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =     12.560 ms/op
     p(99.9900) =     25.263 ms/op
     p(99.9990) =     27.165 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.898 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 4.194 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.793 ±(99.9%) 0.011 ms/op
Iteration   1: 3.787 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.134 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   4.112 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   7.602 ms/op
                 listUser·p0.999:  15.892 ms/op
                 listUser·p0.9999: 27.150 ms/op
                 listUser·p1.00:   28.901 ms/op

Iteration   2: 3.732 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.091 ms/op
                 listUser·p0.50:   3.576 ms/op
                 listUser·p0.90:   4.133 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   6.554 ms/op
                 listUser·p0.999:  13.112 ms/op
                 listUser·p0.9999: 14.528 ms/op
                 listUser·p1.00:   14.680 ms/op

Iteration   3: 3.869 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.400 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.166 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   7.938 ms/op
                 listUser·p0.999:  13.763 ms/op
                 listUser·p0.9999: 19.914 ms/op
                 listUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252713
  mean =      3.795 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 243456 
    [ 5.000,  7.500) = 6839 
    [ 7.500, 10.000) = 1610 
    [10.000, 12.500) = 306 
    [12.500, 15.000) = 315 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      2.091 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.141 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      7.406 ms/op
     p(99.9000) =     13.779 ms/op
     p(99.9900) =     25.559 ms/op
     p(99.9990) =     27.649 ms/op
     p(99.9999) =     28.901 ms/op
    p(100.0000) =     28.901 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.153 ± 4.007  ops/ms
ClientPb.existUser                       thrpt       3  10.338 ± 6.913  ops/ms
ClientPb.getUser                         thrpt       3  10.111 ± 6.107  ops/ms
ClientPb.listUser                        thrpt       3   8.518 ± 2.085  ops/ms
ClientPb.createUser                       avgt       3   3.217 ± 0.390   ms/op
ClientPb.existUser                        avgt       3   2.995 ± 1.019   ms/op
ClientPb.getUser                          avgt       3   3.192 ± 1.313   ms/op
ClientPb.listUser                         avgt       3   3.723 ± 1.209   ms/op
ClientPb.createUser                     sample  306393   3.129 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.988           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.035           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.482           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.736           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.374           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.100           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.791           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.150           ms/op
ClientPb.existUser                      sample  303904   3.157 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.983           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.420           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.764           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.448           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.435           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.140           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.361           ms/op
ClientPb.getUser                        sample  300478   3.195 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.805           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.600           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.891           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.628           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.560           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.263           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.460           ms/op
ClientPb.listUser                       sample  252713   3.795 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.091           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.621           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.141           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.406           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.779           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.559           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.901           ms/op
