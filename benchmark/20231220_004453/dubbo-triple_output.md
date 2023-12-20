# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.807 ops/ms
# Warmup Iteration   2: 12.476 ops/ms
# Warmup Iteration   3: 12.674 ops/ms
Iteration   1: 12.879 ops/ms
Iteration   2: 13.022 ops/ms
Iteration   3: 13.000 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.967 ±(99.9%) 1.409 ops/ms [Average]
  (min, avg, max) = (12.879, 12.967, 13.022), stdev = 0.077
  CI (99.9%): [11.558, 14.377] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 8.598 ops/ms
# Warmup Iteration   2: 13.480 ops/ms
# Warmup Iteration   3: 13.387 ops/ms
Iteration   1: 13.521 ops/ms
Iteration   2: 13.553 ops/ms
Iteration   3: 13.524 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.533 ±(99.9%) 0.316 ops/ms [Average]
  (min, avg, max) = (13.521, 13.533, 13.553), stdev = 0.017
  CI (99.9%): [13.217, 13.848] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.034 ops/ms
# Warmup Iteration   2: 12.762 ops/ms
# Warmup Iteration   3: 12.831 ops/ms
Iteration   1: 12.956 ops/ms
Iteration   2: 12.906 ops/ms
Iteration   3: 12.782 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.881 ±(99.9%) 1.627 ops/ms [Average]
  (min, avg, max) = (12.782, 12.881, 12.956), stdev = 0.089
  CI (99.9%): [11.254, 14.509] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.904 ops/ms
# Warmup Iteration   2: 10.677 ops/ms
# Warmup Iteration   3: 10.704 ops/ms
Iteration   1: 10.674 ops/ms
Iteration   2: 10.678 ops/ms
Iteration   3: 10.655 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.669 ±(99.9%) 0.221 ops/ms [Average]
  (min, avg, max) = (10.655, 10.669, 10.678), stdev = 0.012
  CI (99.9%): [10.447, 10.890] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.011 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.536 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.004 ms/op
Iteration   1: 2.513 ±(99.9%) 0.004 ms/op
Iteration   2: 2.551 ±(99.9%) 0.003 ms/op
Iteration   3: 2.533 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.532 ±(99.9%) 0.347 ms/op [Average]
  (min, avg, max) = (2.513, 2.532, 2.551), stdev = 0.019
  CI (99.9%): [2.186, 2.879] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.561 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.405 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.394 ±(99.9%) 0.003 ms/op
Iteration   1: 2.402 ±(99.9%) 0.004 ms/op
Iteration   2: 2.418 ±(99.9%) 0.004 ms/op
Iteration   3: 2.405 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.408 ±(99.9%) 0.156 ms/op [Average]
  (min, avg, max) = (2.402, 2.408, 2.418), stdev = 0.009
  CI (99.9%): [2.252, 2.564] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.785 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.517 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.455 ±(99.9%) 0.004 ms/op
Iteration   1: 2.503 ±(99.9%) 0.004 ms/op
Iteration   2: 2.447 ±(99.9%) 0.004 ms/op
Iteration   3: 2.481 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.477 ±(99.9%) 0.515 ms/op [Average]
  (min, avg, max) = (2.447, 2.477, 2.503), stdev = 0.028
  CI (99.9%): [1.962, 2.992] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.670 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.977 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.929 ±(99.9%) 0.005 ms/op
Iteration   1: 2.952 ±(99.9%) 0.006 ms/op
Iteration   2: 2.944 ±(99.9%) 0.006 ms/op
Iteration   3: 2.952 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.949 ±(99.9%) 0.087 ms/op [Average]
  (min, avg, max) = (2.944, 2.949, 2.952), stdev = 0.005
  CI (99.9%): [2.863, 3.036] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 3.969 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.640 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.006 ms/op
Iteration   1: 2.498 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.945 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.030 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  11.125 ms/op
                 createUser·p0.9999: 19.219 ms/op
                 createUser·p1.00:   20.218 ms/op

Iteration   2: 2.459 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.896 ms/op
                 createUser·p0.50:   2.523 ms/op
                 createUser·p0.90:   2.982 ms/op
                 createUser·p0.95:   3.084 ms/op
                 createUser·p0.99:   3.518 ms/op
                 createUser·p0.999:  7.994 ms/op
                 createUser·p0.9999: 11.993 ms/op
                 createUser·p1.00:   12.747 ms/op

Iteration   3: 2.471 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.968 ms/op
                 createUser·p0.50:   2.523 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.842 ms/op
                 createUser·p0.999:  6.927 ms/op
                 createUser·p0.9999: 12.357 ms/op
                 createUser·p1.00:   13.091 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 387477
  mean =      2.476 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 190967 
    [ 2.500,  5.000) = 195507 
    [ 5.000,  7.500) = 569 
    [ 7.500, 10.000) = 115 
    [10.000, 12.500) = 225 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.858 ms/op
     p(99.9000) =      8.303 ms/op
     p(99.9900) =     13.410 ms/op
     p(99.9990) =     19.964 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.644 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.438 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.434 ±(99.9%) 0.005 ms/op
Iteration   1: 2.415 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.798 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.486 ms/op
                 existUser·p0.999:  5.469 ms/op
                 existUser·p0.9999: 14.086 ms/op
                 existUser·p1.00:   15.122 ms/op

Iteration   2: 2.406 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.909 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.920 ms/op
                 existUser·p0.95:   3.019 ms/op
                 existUser·p0.99:   3.523 ms/op
                 existUser·p0.999:  5.226 ms/op
                 existUser·p0.9999: 13.393 ms/op
                 existUser·p1.00:   14.057 ms/op

Iteration   3: 2.431 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.029 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.928 ms/op
                 existUser·p0.999:  6.995 ms/op
                 existUser·p0.9999: 12.499 ms/op
                 existUser·p1.00:   13.058 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 396676
  mean =      2.418 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 200443 
    [ 2.500,  3.750) = 192860 
    [ 3.750,  5.000) = 2672 
    [ 5.000,  6.250) = 270 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 111 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      2.478 ms/op
     p(90.0000) =      2.937 ms/op
     p(95.0000) =      3.043 ms/op
     p(99.0000) =      3.629 ms/op
     p(99.9000) =      5.805 ms/op
     p(99.9900) =     13.566 ms/op
     p(99.9990) =     14.914 ms/op
     p(99.9999) =     15.122 ms/op
    p(100.0000) =     15.122 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.845 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.554 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.453 ±(99.9%) 0.005 ms/op
Iteration   1: 2.458 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.873 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   2.982 ms/op
                 getUser·p0.95:   3.105 ms/op
                 getUser·p0.99:   3.940 ms/op
                 getUser·p0.999:  7.937 ms/op
                 getUser·p0.9999: 14.401 ms/op
                 getUser·p1.00:   15.139 ms/op

Iteration   2: 2.428 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.762 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   2.953 ms/op
                 getUser·p0.95:   3.060 ms/op
                 getUser·p0.99:   3.584 ms/op
                 getUser·p0.999:  7.869 ms/op
                 getUser·p0.9999: 12.158 ms/op
                 getUser·p1.00:   12.927 ms/op

Iteration   3: 2.450 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.839 ms/op
                 getUser·p0.50:   2.462 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   4.108 ms/op
                 getUser·p0.999:  6.907 ms/op
                 getUser·p0.9999: 10.518 ms/op
                 getUser·p1.00:   10.748 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 392209
  mean =      2.445 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 99 
    [ 1.250,  2.500) = 198305 
    [ 2.500,  3.750) = 189287 
    [ 3.750,  5.000) = 3411 
    [ 5.000,  6.250) = 636 
    [ 6.250,  7.500) = 76 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 135 
    [11.250, 12.500) = 107 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      2.474 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.858 ms/op
     p(99.9000) =      7.749 ms/op
     p(99.9900) =     13.333 ms/op
     p(99.9990) =     14.719 ms/op
     p(99.9999) =     15.139 ms/op
    p(100.0000) =     15.139 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.556 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.064 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.945 ±(99.9%) 0.008 ms/op
Iteration   1: 2.951 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.866 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.797 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  9.819 ms/op
                 listUser·p0.9999: 11.433 ms/op
                 listUser·p1.00:   13.418 ms/op

Iteration   2: 2.946 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.852 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.768 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   5.415 ms/op
                 listUser·p0.999:  10.067 ms/op
                 listUser·p0.9999: 13.044 ms/op
                 listUser·p1.00:   13.615 ms/op

Iteration   3: 2.923 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.729 ms/op
                 listUser·p0.50:   2.875 ms/op
                 listUser·p0.90:   3.736 ms/op
                 listUser·p0.95:   4.211 ms/op
                 listUser·p0.99:   5.448 ms/op
                 listUser·p0.999:  9.388 ms/op
                 listUser·p0.9999: 12.508 ms/op
                 listUser·p1.00:   13.074 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 326268
  mean =      2.940 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 173 
    [ 1.250,  2.500) = 105296 
    [ 2.500,  3.750) = 187322 
    [ 3.750,  5.000) = 27274 
    [ 5.000,  6.250) = 5032 
    [ 6.250,  7.500) = 510 
    [ 7.500,  8.750) = 178 
    [ 8.750, 10.000) = 195 
    [10.000, 11.250) = 166 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.729 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =      9.810 ms/op
     p(99.9900) =     12.491 ms/op
     p(99.9990) =     13.418 ms/op
     p(99.9999) =     13.615 ms/op
    p(100.0000) =     13.615 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.967 ± 1.409  ops/ms
ClientPb.existUser                       thrpt       3  13.533 ± 0.316  ops/ms
ClientPb.getUser                         thrpt       3  12.881 ± 1.627  ops/ms
ClientPb.listUser                        thrpt       3  10.669 ± 0.221  ops/ms
ClientPb.createUser                       avgt       3   2.532 ± 0.347   ms/op
ClientPb.existUser                        avgt       3   2.408 ± 0.156   ms/op
ClientPb.getUser                          avgt       3   2.477 ± 0.515   ms/op
ClientPb.listUser                         avgt       3   2.949 ± 0.087   ms/op
ClientPb.createUser                     sample  387477   2.476 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.896           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.531           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.002           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.125           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.858           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.303           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.410           ms/op
ClientPb.createUser:createUser·p1.00    sample          20.218           ms/op
ClientPb.existUser                      sample  396676   2.418 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.798           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.478           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.937           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.629           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.805           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.566           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.122           ms/op
ClientPb.getUser                        sample  392209   2.445 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.762           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.474           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.974           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.858           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.749           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.333           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.139           ms/op
ClientPb.listUser                       sample  326268   2.940 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.729           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.888           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.764           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.252           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.448           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.810           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.491           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.615           ms/op
