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
# Warmup Iteration   1: 2.591 ops/ms
# Warmup Iteration   2: 6.118 ops/ms
# Warmup Iteration   3: 8.916 ops/ms
Iteration   1: 9.721 ops/ms
Iteration   2: 10.015 ops/ms
Iteration   3: 9.908 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.881 ±(99.9%) 2.718 ops/ms [Average]
  (min, avg, max) = (9.721, 9.881, 10.015), stdev = 0.149
  CI (99.9%): [7.163, 12.599] (assumes normal distribution)


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
# Warmup Iteration   1: 3.609 ops/ms
# Warmup Iteration   2: 9.595 ops/ms
# Warmup Iteration   3: 9.922 ops/ms
Iteration   1: 10.417 ops/ms
Iteration   2: 10.563 ops/ms
Iteration   3: 10.371 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.450 ±(99.9%) 1.826 ops/ms [Average]
  (min, avg, max) = (10.371, 10.450, 10.563), stdev = 0.100
  CI (99.9%): [8.625, 12.276] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.846 ops/ms
# Warmup Iteration   2: 9.358 ops/ms
# Warmup Iteration   3: 9.818 ops/ms
Iteration   1: 9.918 ops/ms
Iteration   2: 10.277 ops/ms
Iteration   3: 9.991 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.062 ±(99.9%) 3.456 ops/ms [Average]
  (min, avg, max) = (9.918, 10.062, 10.277), stdev = 0.189
  CI (99.9%): [6.606, 13.518] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.225 ops/ms
# Warmup Iteration   2: 7.850 ops/ms
# Warmup Iteration   3: 8.141 ops/ms
Iteration   1: 8.636 ops/ms
Iteration   2: 8.752 ops/ms
Iteration   3: 8.543 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.644 ±(99.9%) 1.912 ops/ms [Average]
  (min, avg, max) = (8.543, 8.644, 8.752), stdev = 0.105
  CI (99.9%): [6.731, 10.556] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.833 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.505 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.303 ±(99.9%) 0.006 ms/op
Iteration   1: 3.212 ±(99.9%) 0.005 ms/op
Iteration   2: 3.207 ±(99.9%) 0.005 ms/op
Iteration   3: 3.092 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.171 ±(99.9%) 1.241 ms/op [Average]
  (min, avg, max) = (3.092, 3.171, 3.212), stdev = 0.068
  CI (99.9%): [1.929, 4.412] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 6.849 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.308 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.167 ±(99.9%) 0.003 ms/op
Iteration   1: 3.024 ±(99.9%) 0.003 ms/op
Iteration   2: 3.092 ±(99.9%) 0.007 ms/op
Iteration   3: 3.007 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.041 ±(99.9%) 0.818 ms/op [Average]
  (min, avg, max) = (3.007, 3.041, 3.092), stdev = 0.045
  CI (99.9%): [2.223, 3.860] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.460 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.393 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.182 ±(99.9%) 0.006 ms/op
Iteration   1: 3.115 ±(99.9%) 0.007 ms/op
Iteration   2: 3.106 ±(99.9%) 0.006 ms/op
Iteration   3: 3.118 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.113 ±(99.9%) 0.116 ms/op [Average]
  (min, avg, max) = (3.106, 3.113, 3.118), stdev = 0.006
  CI (99.9%): [2.996, 3.229] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.126 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.971 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.826 ±(99.9%) 0.006 ms/op
Iteration   1: 3.742 ±(99.9%) 0.008 ms/op
Iteration   2: 3.672 ±(99.9%) 0.006 ms/op
Iteration   3: 3.740 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.718 ±(99.9%) 0.723 ms/op [Average]
  (min, avg, max) = (3.672, 3.718, 3.742), stdev = 0.040
  CI (99.9%): [2.994, 4.441] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.997 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.633 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.219 ±(99.9%) 0.009 ms/op
Iteration   1: 3.151 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.118 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   5.464 ms/op
                 createUser·p0.999:  19.333 ms/op
                 createUser·p0.9999: 21.430 ms/op
                 createUser·p1.00:   22.053 ms/op

Iteration   2: 3.144 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.499 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  9.142 ms/op
                 createUser·p0.9999: 20.758 ms/op
                 createUser·p1.00:   21.299 ms/op

Iteration   3: 3.140 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.399 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  12.622 ms/op
                 createUser·p0.9999: 18.397 ms/op
                 createUser·p1.00:   19.169 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 305096
  mean =      3.145 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15097 
    [ 2.500,  5.000) = 284307 
    [ 5.000,  7.500) = 4890 
    [ 7.500, 10.000) = 395 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 165 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.118 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =     15.711 ms/op
     p(99.9900) =     21.037 ms/op
     p(99.9990) =     21.889 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.354 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 3.359 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.125 ±(99.9%) 0.007 ms/op
Iteration   1: 3.023 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.128 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   5.218 ms/op
                 existUser·p0.999:  8.929 ms/op
                 existUser·p0.9999: 21.012 ms/op
                 existUser·p1.00:   21.955 ms/op

Iteration   2: 3.032 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.165 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.191 ms/op
                 existUser·p0.95:   3.420 ms/op
                 existUser·p0.99:   5.587 ms/op
                 existUser·p0.999:  15.168 ms/op
                 existUser·p0.9999: 20.920 ms/op
                 existUser·p1.00:   21.529 ms/op

Iteration   3: 3.068 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.395 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.244 ms/op
                 existUser·p0.95:   3.416 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  13.094 ms/op
                 existUser·p0.9999: 23.560 ms/op
                 existUser·p1.00:   25.264 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 315763
  mean =      3.041 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16292 
    [ 2.500,  5.000) = 294383 
    [ 5.000,  7.500) = 4253 
    [ 7.500, 10.000) = 404 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.128 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.240 ms/op
     p(95.0000) =      3.465 ms/op
     p(99.0000) =      5.366 ms/op
     p(99.9000) =     15.024 ms/op
     p(99.9900) =     22.807 ms/op
     p(99.9990) =     25.155 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.037 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.407 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.264 ±(99.9%) 0.009 ms/op
Iteration   1: 3.134 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.192 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.428 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   5.767 ms/op
                 getUser·p0.999:  16.333 ms/op
                 getUser·p0.9999: 28.881 ms/op
                 getUser·p1.00:   30.015 ms/op

Iteration   2: 3.182 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.128 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   5.300 ms/op
                 getUser·p0.999:  15.791 ms/op
                 getUser·p0.9999: 25.850 ms/op
                 getUser·p1.00:   26.640 ms/op

Iteration   3: 3.092 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.755 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.359 ms/op
                 getUser·p0.95:   3.539 ms/op
                 getUser·p0.99:   5.095 ms/op
                 getUser·p0.999:  9.372 ms/op
                 getUser·p0.9999: 18.285 ms/op
                 getUser·p1.00:   18.481 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 306084
  mean =      3.136 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14236 
    [ 2.500,  5.000) = 287905 
    [ 5.000,  7.500) = 2945 
    [ 7.500, 10.000) = 517 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 140 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.128 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.658 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =     16.056 ms/op
     p(99.9900) =     28.049 ms/op
     p(99.9990) =     29.684 ms/op
     p(99.9999) =     30.015 ms/op
    p(100.0000) =     30.015 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.919 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 4.083 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.858 ±(99.9%) 0.012 ms/op
Iteration   1: 3.958 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.374 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   7.102 ms/op
                 listUser·p0.999:  13.566 ms/op
                 listUser·p0.9999: 17.554 ms/op
                 listUser·p1.00:   18.874 ms/op

Iteration   2: 3.850 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.112 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   7.684 ms/op
                 listUser·p0.999:  14.614 ms/op
                 listUser·p0.9999: 17.652 ms/op
                 listUser·p1.00:   19.628 ms/op

Iteration   3: 3.890 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.376 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  14.022 ms/op
                 listUser·p0.9999: 17.203 ms/op
                 listUser·p1.00:   17.269 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 246102
  mean =      3.899 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 34 
    [ 2.500,  3.750) = 104159 
    [ 3.750,  5.000) = 133344 
    [ 5.000,  6.250) = 2631 
    [ 6.250,  7.500) = 3671 
    [ 7.500,  8.750) = 972 
    [ 8.750, 10.000) = 446 
    [10.000, 11.250) = 255 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 240 
    [13.750, 15.000) = 91 
    [15.000, 16.250) = 60 
    [16.250, 17.500) = 84 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.374 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      7.365 ms/op
     p(99.9000) =     13.861 ms/op
     p(99.9900) =     17.282 ms/op
     p(99.9990) =     19.228 ms/op
     p(99.9999) =     19.628 ms/op
    p(100.0000) =     19.628 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.881 ± 2.718  ops/ms
ClientPb.existUser                       thrpt       3  10.450 ± 1.826  ops/ms
ClientPb.getUser                         thrpt       3  10.062 ± 3.456  ops/ms
ClientPb.listUser                        thrpt       3   8.644 ± 1.912  ops/ms
ClientPb.createUser                       avgt       3   3.171 ± 1.241   ms/op
ClientPb.existUser                        avgt       3   3.041 ± 0.818   ms/op
ClientPb.getUser                          avgt       3   3.113 ± 0.116   ms/op
ClientPb.listUser                         avgt       3   3.718 ± 0.723   ms/op
ClientPb.createUser                     sample  305096   3.145 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.118           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.052           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.473           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.817           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.448           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.711           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.037           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.053           ms/op
ClientPb.existUser                      sample  315763   3.041 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.128           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.957           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.240           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.465           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.366           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.024           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.807           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.264           ms/op
ClientPb.getUser                        sample  306084   3.136 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.128           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.043           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.441           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.658           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.415           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.056           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.049           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.015           ms/op
ClientPb.listUser                       sample  246102   3.899 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.374           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.777           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.612           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.365           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.861           ms/op
ClientPb.listUser:listUser·p0.9999      sample          17.282           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.628           ms/op
