# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.531 ops/ms
# Warmup Iteration   2: 6.163 ops/ms
# Warmup Iteration   3: 8.753 ops/ms
Iteration   1: 9.422 ops/ms
Iteration   2: 9.414 ops/ms
Iteration   3: 9.984 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.607 ±(99.9%) 5.961 ops/ms [Average]
  (min, avg, max) = (9.414, 9.607, 9.984), stdev = 0.327
  CI (99.9%): [3.646, 15.568] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.257 ops/ms
# Warmup Iteration   2: 9.213 ops/ms
# Warmup Iteration   3: 9.655 ops/ms
Iteration   1: 9.830 ops/ms
Iteration   2: 10.333 ops/ms
Iteration   3: 10.197 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.120 ±(99.9%) 4.739 ops/ms [Average]
  (min, avg, max) = (9.830, 10.120, 10.333), stdev = 0.260
  CI (99.9%): [5.381, 14.859] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.108 ops/ms
# Warmup Iteration   2: 8.756 ops/ms
# Warmup Iteration   3: 9.586 ops/ms
Iteration   1: 9.925 ops/ms
Iteration   2: 10.061 ops/ms
Iteration   3: 9.776 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.920 ±(99.9%) 2.604 ops/ms [Average]
  (min, avg, max) = (9.776, 9.920, 10.061), stdev = 0.143
  CI (99.9%): [7.317, 12.524] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 3.025 ops/ms
# Warmup Iteration   2: 7.507 ops/ms
# Warmup Iteration   3: 8.207 ops/ms
Iteration   1: 8.359 ops/ms
Iteration   2: 8.381 ops/ms
Iteration   3: 8.229 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.323 ±(99.9%) 1.491 ops/ms [Average]
  (min, avg, max) = (8.229, 8.323, 8.381), stdev = 0.082
  CI (99.9%): [6.832, 9.814] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.005 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.567 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.363 ±(99.9%) 0.002 ms/op
Iteration   1: 3.295 ±(99.9%) 0.004 ms/op
Iteration   2: 3.243 ±(99.9%) 0.003 ms/op
Iteration   3: 3.234 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.257 ±(99.9%) 0.604 ms/op [Average]
  (min, avg, max) = (3.234, 3.257, 3.295), stdev = 0.033
  CI (99.9%): [2.654, 3.861] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 7.605 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.378 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.116 ±(99.9%) 0.002 ms/op
Iteration   1: 3.180 ±(99.9%) 0.002 ms/op
Iteration   2: 3.099 ±(99.9%) 0.003 ms/op
Iteration   3: 3.142 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.140 ±(99.9%) 0.740 ms/op [Average]
  (min, avg, max) = (3.099, 3.140, 3.180), stdev = 0.041
  CI (99.9%): [2.401, 3.880] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 7.673 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.420 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.259 ±(99.9%) 0.002 ms/op
Iteration   1: 3.317 ±(99.9%) 0.002 ms/op
Iteration   2: 3.201 ±(99.9%) 0.002 ms/op
Iteration   3: 3.256 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.258 ±(99.9%) 1.063 ms/op [Average]
  (min, avg, max) = (3.201, 3.258, 3.317), stdev = 0.058
  CI (99.9%): [2.195, 4.322] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.404 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.069 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.856 ±(99.9%) 0.003 ms/op
Iteration   1: 3.861 ±(99.9%) 0.004 ms/op
Iteration   2: 3.773 ±(99.9%) 0.005 ms/op
Iteration   3: 3.789 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.808 ±(99.9%) 0.850 ms/op [Average]
  (min, avg, max) = (3.773, 3.808, 3.861), stdev = 0.047
  CI (99.9%): [2.958, 4.658] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.375 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.757 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.233 ±(99.9%) 0.008 ms/op
Iteration   1: 3.282 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.188 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   6.149 ms/op
                 createUser·p0.999:  17.564 ms/op
                 createUser·p0.9999: 21.480 ms/op
                 createUser·p1.00:   21.955 ms/op

Iteration   2: 3.309 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.468 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.744 ms/op
                 createUser·p0.95:   4.022 ms/op
                 createUser·p0.99:   5.775 ms/op
                 createUser·p0.999:  18.166 ms/op
                 createUser·p0.9999: 26.846 ms/op
                 createUser·p1.00:   27.918 ms/op

Iteration   3: 3.160 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.524 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.428 ms/op
                 createUser·p0.95:   3.654 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  15.150 ms/op
                 createUser·p0.9999: 20.775 ms/op
                 createUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295559
  mean =      3.249 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21065 
    [ 2.500,  5.000) = 269559 
    [ 5.000,  7.500) = 3828 
    [ 7.500, 10.000) = 441 
    [10.000, 12.500) = 248 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 133 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.524 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     15.827 ms/op
     p(99.9900) =     24.478 ms/op
     p(99.9990) =     27.264 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.798 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.296 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.156 ±(99.9%) 0.008 ms/op
Iteration   1: 3.094 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.360 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   5.333 ms/op
                 existUser·p0.999:  9.312 ms/op
                 existUser·p0.9999: 20.240 ms/op
                 existUser·p1.00:   21.135 ms/op

Iteration   2: 3.146 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.305 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.706 ms/op
                 existUser·p0.99:   5.418 ms/op
                 existUser·p0.999:  13.566 ms/op
                 existUser·p0.9999: 21.982 ms/op
                 existUser·p1.00:   23.134 ms/op

Iteration   3: 3.163 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.466 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   5.259 ms/op
                 existUser·p0.999:  13.058 ms/op
                 existUser·p0.9999: 20.935 ms/op
                 existUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 306074
  mean =      3.134 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17851 
    [ 2.500,  5.000) = 283962 
    [ 5.000,  7.500) = 3548 
    [ 7.500, 10.000) = 325 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 119 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.305 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.428 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      5.349 ms/op
     p(99.9000) =     13.058 ms/op
     p(99.9900) =     21.378 ms/op
     p(99.9990) =     22.831 ms/op
     p(99.9999) =     23.134 ms/op
    p(100.0000) =     23.134 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.371 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.568 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.341 ±(99.9%) 0.009 ms/op
Iteration   1: 3.309 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.184 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   6.439 ms/op
                 getUser·p0.999:  20.163 ms/op
                 getUser·p0.9999: 32.331 ms/op
                 getUser·p1.00:   34.406 ms/op

Iteration   2: 3.239 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.393 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.678 ms/op
                 getUser·p0.999:  11.043 ms/op
                 getUser·p0.9999: 22.090 ms/op
                 getUser·p1.00:   23.036 ms/op

Iteration   3: 3.348 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.255 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   6.053 ms/op
                 getUser·p0.999:  15.532 ms/op
                 getUser·p0.9999: 21.594 ms/op
                 getUser·p1.00:   23.429 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 290812
  mean =      3.298 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8373 
    [ 2.500,  5.000) = 276925 
    [ 5.000,  7.500) = 4501 
    [ 7.500, 10.000) = 448 
    [10.000, 12.500) = 169 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 141 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.184 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      5.841 ms/op
     p(99.9000) =     16.495 ms/op
     p(99.9900) =     29.614 ms/op
     p(99.9990) =     33.900 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.917 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.338 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.939 ±(99.9%) 0.011 ms/op
Iteration   1: 3.868 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.339 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   6.545 ms/op
                 listUser·p0.999:  18.558 ms/op
                 listUser·p0.9999: 23.386 ms/op
                 listUser·p1.00:   24.281 ms/op

Iteration   2: 3.868 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.231 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   7.591 ms/op
                 listUser·p0.999:  13.566 ms/op
                 listUser·p0.9999: 17.727 ms/op
                 listUser·p1.00:   17.793 ms/op

Iteration   3: 3.823 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.363 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.162 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  12.851 ms/op
                 listUser·p0.9999: 14.792 ms/op
                 listUser·p1.00:   19.399 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 248943
  mean =      3.853 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 81 
    [ 2.500,  5.000) = 242292 
    [ 5.000,  7.500) = 4882 
    [ 7.500, 10.000) = 942 
    [10.000, 12.500) = 299 
    [12.500, 15.000) = 308 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.231 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      6.902 ms/op
     p(99.9000) =     13.568 ms/op
     p(99.9900) =     21.273 ms/op
     p(99.9990) =     24.281 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.607 ± 5.961  ops/ms
ClientPb.existUser                       thrpt       3  10.120 ± 4.739  ops/ms
ClientPb.getUser                         thrpt       3   9.920 ± 2.604  ops/ms
ClientPb.listUser                        thrpt       3   8.323 ± 1.491  ops/ms
ClientPb.createUser                       avgt       3   3.257 ± 0.604   ms/op
ClientPb.existUser                        avgt       3   3.140 ± 0.740   ms/op
ClientPb.getUser                          avgt       3   3.258 ± 1.063   ms/op
ClientPb.listUser                         avgt       3   3.808 ± 0.850   ms/op
ClientPb.createUser                     sample  295559   3.249 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.524           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.588           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.867           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.710           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.827           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.478           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.918           ms/op
ClientPb.existUser                      sample  306074   3.134 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.305           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.428           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.349           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.058           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.378           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.134           ms/op
ClientPb.getUser                        sample  290812   3.298 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.184           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.199           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.637           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.883           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.841           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.495           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.614           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.406           ms/op
ClientPb.listUser                       sample  248943   3.853 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.231           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.748           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.202           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.902           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.568           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.273           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.281           ms/op
