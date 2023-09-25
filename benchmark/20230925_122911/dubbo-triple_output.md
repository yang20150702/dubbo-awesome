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
# Warmup Iteration   1: 2.519 ops/ms
# Warmup Iteration   2: 5.845 ops/ms
# Warmup Iteration   3: 8.869 ops/ms
Iteration   1: 9.639 ops/ms
Iteration   2: 9.786 ops/ms
Iteration   3: 9.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.735 ±(99.9%) 1.518 ops/ms [Average]
  (min, avg, max) = (9.639, 9.735, 9.786), stdev = 0.083
  CI (99.9%): [8.217, 11.253] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.586 ops/ms
# Warmup Iteration   2: 9.334 ops/ms
# Warmup Iteration   3: 10.077 ops/ms
Iteration   1: 10.095 ops/ms
Iteration   2: 10.217 ops/ms
Iteration   3: 10.410 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.241 ±(99.9%) 2.897 ops/ms [Average]
  (min, avg, max) = (10.095, 10.241, 10.410), stdev = 0.159
  CI (99.9%): [7.344, 13.138] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.612 ops/ms
# Warmup Iteration   2: 8.962 ops/ms
# Warmup Iteration   3: 9.843 ops/ms
Iteration   1: 9.792 ops/ms
Iteration   2: 9.774 ops/ms
Iteration   3: 9.908 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.825 ±(99.9%) 1.322 ops/ms [Average]
  (min, avg, max) = (9.774, 9.825, 9.908), stdev = 0.072
  CI (99.9%): [8.503, 11.146] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.408 ops/ms
# Warmup Iteration   2: 7.753 ops/ms
# Warmup Iteration   3: 8.268 ops/ms
Iteration   1: 8.307 ops/ms
Iteration   2: 8.403 ops/ms
Iteration   3: 8.377 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.363 ±(99.9%) 0.905 ops/ms [Average]
  (min, avg, max) = (8.307, 8.363, 8.403), stdev = 0.050
  CI (99.9%): [7.458, 9.267] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.754 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.634 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.443 ±(99.9%) 0.004 ms/op
Iteration   1: 3.265 ±(99.9%) 0.003 ms/op
Iteration   2: 3.252 ±(99.9%) 0.003 ms/op
Iteration   3: 3.191 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.236 ±(99.9%) 0.721 ms/op [Average]
  (min, avg, max) = (3.191, 3.236, 3.265), stdev = 0.040
  CI (99.9%): [2.515, 3.957] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.517 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.304 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.142 ±(99.9%) 0.001 ms/op
Iteration   1: 3.147 ±(99.9%) 0.002 ms/op
Iteration   2: 3.078 ±(99.9%) 0.003 ms/op
Iteration   3: 3.088 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.104 ±(99.9%) 0.683 ms/op [Average]
  (min, avg, max) = (3.078, 3.104, 3.147), stdev = 0.037
  CI (99.9%): [2.421, 3.787] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.516 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.439 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.323 ±(99.9%) 0.003 ms/op
Iteration   1: 3.157 ±(99.9%) 0.003 ms/op
Iteration   2: 3.169 ±(99.9%) 0.003 ms/op
Iteration   3: 3.233 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.186 ±(99.9%) 0.748 ms/op [Average]
  (min, avg, max) = (3.157, 3.186, 3.233), stdev = 0.041
  CI (99.9%): [2.438, 3.935] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.630 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.988 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.870 ±(99.9%) 0.003 ms/op
Iteration   1: 3.832 ±(99.9%) 0.005 ms/op
Iteration   2: 3.776 ±(99.9%) 0.006 ms/op
Iteration   3: 3.779 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.796 ±(99.9%) 0.582 ms/op [Average]
  (min, avg, max) = (3.776, 3.796, 3.832), stdev = 0.032
  CI (99.9%): [3.214, 4.377] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.420 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.637 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.225 ±(99.9%) 0.008 ms/op
Iteration   1: 3.237 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.593 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.998 ms/op
                 createUser·p0.99:   6.177 ms/op
                 createUser·p0.999:  15.732 ms/op
                 createUser·p0.9999: 24.580 ms/op
                 createUser·p1.00:   24.642 ms/op

Iteration   2: 3.193 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.436 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   5.194 ms/op
                 createUser·p0.999:  15.564 ms/op
                 createUser·p0.9999: 19.431 ms/op
                 createUser·p1.00:   20.382 ms/op

Iteration   3: 3.297 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.704 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   5.276 ms/op
                 createUser·p0.999:  16.499 ms/op
                 createUser·p0.9999: 18.655 ms/op
                 createUser·p1.00:   19.694 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295745
  mean =      3.242 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16686 
    [ 2.500,  5.000) = 273853 
    [ 5.000,  7.500) = 4000 
    [ 7.500, 10.000) = 547 
    [10.000, 12.500) = 240 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 245 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.436 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     15.745 ms/op
     p(99.9900) =     24.347 ms/op
     p(99.9990) =     24.609 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


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
# Warmup Iteration   1: 8.688 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.389 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.240 ±(99.9%) 0.008 ms/op
Iteration   1: 3.226 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.981 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   5.395 ms/op
                 existUser·p0.999:  11.696 ms/op
                 existUser·p0.9999: 20.447 ms/op
                 existUser·p1.00:   20.644 ms/op

Iteration   2: 3.290 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.397 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   4.108 ms/op
                 existUser·p0.99:   6.906 ms/op
                 existUser·p0.999:  13.074 ms/op
                 existUser·p0.9999: 22.321 ms/op
                 existUser·p1.00:   23.298 ms/op

Iteration   3: 3.155 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.446 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   5.218 ms/op
                 existUser·p0.999:  19.005 ms/op
                 existUser·p0.9999: 27.231 ms/op
                 existUser·p1.00:   29.360 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 297666
  mean =      3.223 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20765 
    [ 2.500,  5.000) = 271427 
    [ 5.000,  7.500) = 4305 
    [ 7.500, 10.000) = 630 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 147 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.981 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      5.997 ms/op
     p(99.9000) =     16.531 ms/op
     p(99.9900) =     22.585 ms/op
     p(99.9990) =     29.068 ms/op
     p(99.9999) =     29.360 ms/op
    p(100.0000) =     29.360 ms/op


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
# Warmup Iteration   1: 8.429 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.426 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.343 ±(99.9%) 0.009 ms/op
Iteration   1: 3.290 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.346 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   6.455 ms/op
                 getUser·p0.999:  18.088 ms/op
                 getUser·p0.9999: 20.087 ms/op
                 getUser·p1.00:   20.480 ms/op

Iteration   2: 3.221 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.815 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.997 ms/op
                 getUser·p0.999:  12.914 ms/op
                 getUser·p0.9999: 23.298 ms/op
                 getUser·p1.00:   23.921 ms/op

Iteration   3: 3.263 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.102 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   5.939 ms/op
                 getUser·p0.999:  14.320 ms/op
                 getUser·p0.9999: 21.856 ms/op
                 getUser·p1.00:   23.429 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294607
  mean =      3.258 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8183 
    [ 2.500,  5.000) = 279946 
    [ 5.000,  7.500) = 5517 
    [ 7.500, 10.000) = 412 
    [10.000, 12.500) = 185 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 139 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      5.947 ms/op
     p(99.9000) =     14.998 ms/op
     p(99.9900) =     22.431 ms/op
     p(99.9990) =     23.859 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


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
# Warmup Iteration   1: 10.284 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 4.185 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.872 ±(99.9%) 0.011 ms/op
Iteration   1: 3.944 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.239 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  17.433 ms/op
                 listUser·p0.9999: 21.591 ms/op
                 listUser·p1.00:   22.086 ms/op

Iteration   2: 3.848 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.616 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.137 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  14.680 ms/op
                 listUser·p0.9999: 18.962 ms/op
                 listUser·p1.00:   20.480 ms/op

Iteration   3: 3.870 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.182 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  13.048 ms/op
                 listUser·p0.9999: 14.315 ms/op
                 listUser·p1.00:   15.139 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 246804
  mean =      3.887 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 65 
    [ 2.500,  5.000) = 238837 
    [ 5.000,  7.500) = 6400 
    [ 7.500, 10.000) = 696 
    [10.000, 12.500) = 308 
    [12.500, 15.000) = 301 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.239 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     14.549 ms/op
     p(99.9900) =     20.359 ms/op
     p(99.9990) =     21.878 ms/op
     p(99.9999) =     22.086 ms/op
    p(100.0000) =     22.086 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.735 ± 1.518  ops/ms
ClientPb.existUser                       thrpt       3  10.241 ± 2.897  ops/ms
ClientPb.getUser                         thrpt       3   9.825 ± 1.322  ops/ms
ClientPb.listUser                        thrpt       3   8.363 ± 0.905  ops/ms
ClientPb.createUser                       avgt       3   3.236 ± 0.721   ms/op
ClientPb.existUser                        avgt       3   3.104 ± 0.683   ms/op
ClientPb.getUser                          avgt       3   3.186 ± 0.748   ms/op
ClientPb.listUser                         avgt       3   3.796 ± 0.582   ms/op
ClientPb.createUser                     sample  295745   3.242 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.436           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.609           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.883           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.603           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.745           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.347           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.642           ms/op
ClientPb.existUser                      sample  297666   3.223 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.981           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.170           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.555           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.863           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.997           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.531           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.585           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.360           ms/op
ClientPb.getUser                        sample  294607   3.258 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.815           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.588           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.867           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.947           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.998           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.431           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.921           ms/op
ClientPb.listUser                       sample  246804   3.887 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.239           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.764           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.243           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.898           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.549           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.359           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.086           ms/op
