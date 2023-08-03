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
# Warmup Iteration   1: 2.268 ops/ms
# Warmup Iteration   2: 6.031 ops/ms
# Warmup Iteration   3: 9.162 ops/ms
Iteration   1: 9.766 ops/ms
Iteration   2: 9.601 ops/ms
Iteration   3: 10.130 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.832 ±(99.9%) 4.934 ops/ms [Average]
  (min, avg, max) = (9.601, 9.832, 10.130), stdev = 0.270
  CI (99.9%): [4.898, 14.766] (assumes normal distribution)


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
# Warmup Iteration   1: 3.120 ops/ms
# Warmup Iteration   2: 9.280 ops/ms
# Warmup Iteration   3: 9.967 ops/ms
Iteration   1: 10.323 ops/ms
Iteration   2: 9.679 ops/ms
Iteration   3: 10.138 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.046 ±(99.9%) 6.048 ops/ms [Average]
  (min, avg, max) = (9.679, 10.046, 10.323), stdev = 0.332
  CI (99.9%): [3.999, 16.094] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.217 ops/ms
# Warmup Iteration   2: 8.278 ops/ms
# Warmup Iteration   3: 9.323 ops/ms
Iteration   1: 9.795 ops/ms
Iteration   2: 9.512 ops/ms
Iteration   3: 9.560 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.622 ±(99.9%) 2.763 ops/ms [Average]
  (min, avg, max) = (9.512, 9.622, 9.795), stdev = 0.151
  CI (99.9%): [6.859, 12.385] (assumes normal distribution)


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
# Warmup Iteration   1: 3.117 ops/ms
# Warmup Iteration   2: 7.426 ops/ms
# Warmup Iteration   3: 8.223 ops/ms
Iteration   1: 8.381 ops/ms
Iteration   2: 8.231 ops/ms
Iteration   3: 8.587 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.400 ±(99.9%) 3.265 ops/ms [Average]
  (min, avg, max) = (8.231, 8.400, 8.587), stdev = 0.179
  CI (99.9%): [5.135, 11.664] (assumes normal distribution)


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
# Warmup Iteration   1: 8.509 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.564 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.455 ±(99.9%) 0.005 ms/op
Iteration   1: 3.222 ±(99.9%) 0.007 ms/op
Iteration   2: 3.335 ±(99.9%) 0.005 ms/op
Iteration   3: 3.223 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.260 ±(99.9%) 1.184 ms/op [Average]
  (min, avg, max) = (3.222, 3.260, 3.335), stdev = 0.065
  CI (99.9%): [2.076, 4.444] (assumes normal distribution)


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
# Warmup Iteration   1: 6.751 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.404 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.145 ±(99.9%) 0.009 ms/op
Iteration   1: 3.144 ±(99.9%) 0.004 ms/op
Iteration   2: 3.149 ±(99.9%) 0.001 ms/op
Iteration   3: 3.244 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.179 ±(99.9%) 1.029 ms/op [Average]
  (min, avg, max) = (3.144, 3.179, 3.244), stdev = 0.056
  CI (99.9%): [2.149, 4.208] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.377 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.581 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.539 ±(99.9%) 0.004 ms/op
Iteration   1: 3.321 ±(99.9%) 0.006 ms/op
Iteration   2: 3.328 ±(99.9%) 0.004 ms/op
Iteration   3: 3.251 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.300 ±(99.9%) 0.774 ms/op [Average]
  (min, avg, max) = (3.251, 3.300, 3.328), stdev = 0.042
  CI (99.9%): [2.526, 4.074] (assumes normal distribution)


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
# Warmup Iteration   1: 10.526 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.386 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.813 ±(99.9%) 0.008 ms/op
Iteration   1: 3.762 ±(99.9%) 0.009 ms/op
Iteration   2: 3.851 ±(99.9%) 0.008 ms/op
Iteration   3: 3.675 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.763 ±(99.9%) 1.609 ms/op [Average]
  (min, avg, max) = (3.675, 3.763, 3.851), stdev = 0.088
  CI (99.9%): [2.153, 5.372] (assumes normal distribution)


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
# Warmup Iteration   1: 7.798 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.683 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.379 ±(99.9%) 0.011 ms/op
Iteration   1: 3.260 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.887 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.416 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   5.890 ms/op
                 createUser·p0.999:  13.677 ms/op
                 createUser·p0.9999: 18.776 ms/op
                 createUser·p1.00:   18.973 ms/op

Iteration   2: 3.267 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.636 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  10.109 ms/op
                 createUser·p0.9999: 27.532 ms/op
                 createUser·p1.00:   28.246 ms/op

Iteration   3: 3.162 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.174 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.338 ms/op
                 createUser·p0.95:   3.584 ms/op
                 createUser·p0.99:   5.521 ms/op
                 createUser·p0.999:  17.629 ms/op
                 createUser·p0.9999: 25.919 ms/op
                 createUser·p1.00:   26.804 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297492
  mean =      3.229 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23058 
    [ 2.500,  5.000) = 268526 
    [ 5.000,  7.500) = 4707 
    [ 7.500, 10.000) = 745 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 170 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 51 

  Percentiles, ms/op:
      p(0.0000) =      0.887 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     16.458 ms/op
     p(99.9900) =     26.419 ms/op
     p(99.9990) =     28.020 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


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
# Warmup Iteration   1: 6.801 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.538 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.383 ±(99.9%) 0.009 ms/op
Iteration   1: 3.244 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.483 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   4.170 ms/op
                 existUser·p0.99:   5.726 ms/op
                 existUser·p0.999:  14.276 ms/op
                 existUser·p0.9999: 25.629 ms/op
                 existUser·p1.00:   27.099 ms/op

Iteration   2: 3.232 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.393 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.703 ms/op
                 existUser·p0.95:   4.121 ms/op
                 existUser·p0.99:   6.013 ms/op
                 existUser·p0.999:  9.077 ms/op
                 existUser·p0.9999: 24.973 ms/op
                 existUser·p1.00:   25.788 ms/op

Iteration   3: 3.133 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.149 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   6.169 ms/op
                 existUser·p0.999:  12.768 ms/op
                 existUser·p0.9999: 35.521 ms/op
                 existUser·p1.00:   37.749 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 299665
  mean =      3.202 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14200 
    [ 2.500,  5.000) = 277695 
    [ 5.000,  7.500) = 6688 
    [ 7.500, 10.000) = 614 
    [10.000, 12.500) = 164 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      6.013 ms/op
     p(99.9000) =     13.107 ms/op
     p(99.9900) =     34.476 ms/op
     p(99.9990) =     37.224 ms/op
     p(99.9999) =     37.749 ms/op
    p(100.0000) =     37.749 ms/op


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
# Warmup Iteration   1: 7.805 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.884 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.370 ±(99.9%) 0.011 ms/op
Iteration   1: 3.262 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.612 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   4.149 ms/op
                 getUser·p0.99:   6.480 ms/op
                 getUser·p0.999:  11.715 ms/op
                 getUser·p0.9999: 22.348 ms/op
                 getUser·p1.00:   23.036 ms/op

Iteration   2: 3.187 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.538 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.588 ms/op
                 getUser·p0.99:   5.366 ms/op
                 getUser·p0.999:  13.200 ms/op
                 getUser·p0.9999: 35.846 ms/op
                 getUser·p1.00:   37.683 ms/op

Iteration   3: 3.208 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.323 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   6.193 ms/op
                 getUser·p0.999:  10.508 ms/op
                 getUser·p0.9999: 28.025 ms/op
                 getUser·p1.00:   29.327 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298058
  mean =      3.219 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2288 
    [ 2.500,  5.000) = 288486 
    [ 5.000,  7.500) = 5910 
    [ 7.500, 10.000) = 943 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.323 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      6.352 ms/op
     p(99.9000) =     12.878 ms/op
     p(99.9900) =     34.485 ms/op
     p(99.9990) =     36.439 ms/op
     p(99.9999) =     37.683 ms/op
    p(100.0000) =     37.683 ms/op


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
# Warmup Iteration   1: 9.151 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.466 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.868 ±(99.9%) 0.011 ms/op
Iteration   1: 3.886 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.704 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.907 ms/op
                 listUser·p0.99:   7.438 ms/op
                 listUser·p0.999:  19.530 ms/op
                 listUser·p0.9999: 21.874 ms/op
                 listUser·p1.00:   23.101 ms/op

Iteration   2: 3.956 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.343 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   8.012 ms/op
                 listUser·p0.999:  15.794 ms/op
                 listUser·p0.9999: 20.080 ms/op
                 listUser·p1.00:   20.775 ms/op

Iteration   3: 3.879 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.294 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   7.807 ms/op
                 listUser·p0.999:  14.994 ms/op
                 listUser·p0.9999: 22.512 ms/op
                 listUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 245690
  mean =      3.907 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 80 
    [ 2.500,  5.000) = 234442 
    [ 5.000,  7.500) = 8288 
    [ 7.500, 10.000) = 2169 
    [10.000, 12.500) = 249 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.343 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      7.758 ms/op
     p(99.9000) =     16.528 ms/op
     p(99.9900) =     21.739 ms/op
     p(99.9990) =     22.580 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.832 ± 4.934  ops/ms
ClientPb.existUser                       thrpt       3  10.046 ± 6.048  ops/ms
ClientPb.getUser                         thrpt       3   9.622 ± 2.763  ops/ms
ClientPb.listUser                        thrpt       3   8.400 ± 3.265  ops/ms
ClientPb.createUser                       avgt       3   3.260 ± 1.184   ms/op
ClientPb.existUser                        avgt       3   3.179 ± 1.029   ms/op
ClientPb.getUser                          avgt       3   3.300 ± 0.774   ms/op
ClientPb.listUser                         avgt       3   3.763 ± 1.609   ms/op
ClientPb.createUser                     sample  297492   3.229 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.887           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.502           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.863           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.677           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.458           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.419           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.246           ms/op
ClientPb.existUser                      sample  299665   3.202 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.149           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.547           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.014           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.013           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.107           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.476           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.749           ms/op
ClientPb.getUser                        sample  298058   3.219 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.323           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.465           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.711           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.352           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.878           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.485           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.683           ms/op
ClientPb.listUser                       sample  245690   3.907 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.343           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.764           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.768           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.758           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.528           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.739           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.101           ms/op
