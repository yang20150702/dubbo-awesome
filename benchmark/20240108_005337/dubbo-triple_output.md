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
# Warmup Iteration   1: 5.588 ops/ms
# Warmup Iteration   2: 12.238 ops/ms
# Warmup Iteration   3: 12.537 ops/ms
Iteration   1: 12.783 ops/ms
Iteration   2: 12.596 ops/ms
Iteration   3: 12.604 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.661 ±(99.9%) 1.926 ops/ms [Average]
  (min, avg, max) = (12.596, 12.661, 12.783), stdev = 0.106
  CI (99.9%): [10.735, 14.587] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.035 ops/ms
# Warmup Iteration   2: 12.861 ops/ms
# Warmup Iteration   3: 13.217 ops/ms
Iteration   1: 13.117 ops/ms
Iteration   2: 13.050 ops/ms
Iteration   3: 13.021 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.063 ±(99.9%) 0.895 ops/ms [Average]
  (min, avg, max) = (13.021, 13.063, 13.117), stdev = 0.049
  CI (99.9%): [12.167, 13.958] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.744 ops/ms
# Warmup Iteration   2: 12.505 ops/ms
# Warmup Iteration   3: 12.766 ops/ms
Iteration   1: 12.986 ops/ms
Iteration   2: 13.048 ops/ms
Iteration   3: 12.999 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.011 ±(99.9%) 0.590 ops/ms [Average]
  (min, avg, max) = (12.986, 13.011, 13.048), stdev = 0.032
  CI (99.9%): [12.421, 13.601] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.791 ops/ms
# Warmup Iteration   2: 10.761 ops/ms
# Warmup Iteration   3: 10.804 ops/ms
Iteration   1: 10.914 ops/ms
Iteration   2: 10.833 ops/ms
Iteration   3: 10.832 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.860 ±(99.9%) 0.859 ops/ms [Average]
  (min, avg, max) = (10.832, 10.860, 10.914), stdev = 0.047
  CI (99.9%): [10.001, 11.719] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.947 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.490 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
Iteration   1: 2.500 ±(99.9%) 0.004 ms/op
Iteration   2: 2.501 ±(99.9%) 0.004 ms/op
Iteration   3: 2.484 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.495 ±(99.9%) 0.173 ms/op [Average]
  (min, avg, max) = (2.484, 2.495, 2.501), stdev = 0.010
  CI (99.9%): [2.322, 2.668] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.853 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.456 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.461 ±(99.9%) 0.005 ms/op
Iteration   1: 2.475 ±(99.9%) 0.005 ms/op
Iteration   2: 2.418 ±(99.9%) 0.004 ms/op
Iteration   3: 2.424 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.439 ±(99.9%) 0.567 ms/op [Average]
  (min, avg, max) = (2.418, 2.439, 2.475), stdev = 0.031
  CI (99.9%): [1.872, 3.006] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.099 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.519 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.465 ±(99.9%) 0.003 ms/op
Iteration   1: 2.456 ±(99.9%) 0.003 ms/op
Iteration   2: 2.452 ±(99.9%) 0.003 ms/op
Iteration   3: 2.488 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.466 ±(99.9%) 0.360 ms/op [Average]
  (min, avg, max) = (2.452, 2.466, 2.488), stdev = 0.020
  CI (99.9%): [2.105, 2.826] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.696 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.059 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.006 ms/op
Iteration   1: 3.005 ±(99.9%) 0.006 ms/op
Iteration   2: 3.018 ±(99.9%) 0.006 ms/op
Iteration   3: 2.973 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.999 ±(99.9%) 0.419 ms/op [Average]
  (min, avg, max) = (2.973, 2.999, 3.018), stdev = 0.023
  CI (99.9%): [2.580, 3.418] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 3.916 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.598 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.006 ms/op
Iteration   1: 2.475 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.954 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.690 ms/op
                 createUser·p0.999:  6.000 ms/op
                 createUser·p0.9999: 13.294 ms/op
                 createUser·p1.00:   13.648 ms/op

Iteration   2: 2.494 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.993 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.912 ms/op
                 createUser·p0.999:  8.561 ms/op
                 createUser·p0.9999: 11.357 ms/op
                 createUser·p1.00:   12.009 ms/op

Iteration   3: 2.461 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.670 ms/op
                 createUser·p0.50:   2.507 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.101 ms/op
                 createUser·p0.99:   3.621 ms/op
                 createUser·p0.999:  8.259 ms/op
                 createUser·p0.9999: 11.798 ms/op
                 createUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 387191
  mean =      2.477 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 190964 
    [ 2.500,  5.000) = 195479 
    [ 5.000,  7.500) = 321 
    [ 7.500, 10.000) = 125 
    [10.000, 12.500) = 235 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.670 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.727 ms/op
     p(99.9000) =      8.249 ms/op
     p(99.9900) =     12.993 ms/op
     p(99.9990) =     13.648 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


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
# Warmup Iteration   1: 3.775 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.424 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.436 ±(99.9%) 0.005 ms/op
Iteration   1: 2.421 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.995 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.576 ms/op
                 existUser·p0.999:  6.101 ms/op
                 existUser·p0.9999: 14.074 ms/op
                 existUser·p1.00:   14.795 ms/op

Iteration   2: 2.402 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.855 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.912 ms/op
                 existUser·p0.95:   3.006 ms/op
                 existUser·p0.99:   3.502 ms/op
                 existUser·p0.999:  7.733 ms/op
                 existUser·p0.9999: 12.999 ms/op
                 existUser·p1.00:   13.582 ms/op

Iteration   3: 2.413 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.797 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   2.920 ms/op
                 existUser·p0.95:   3.011 ms/op
                 existUser·p0.99:   3.449 ms/op
                 existUser·p0.999:  7.758 ms/op
                 existUser·p0.9999: 11.321 ms/op
                 existUser·p1.00:   16.302 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 397554
  mean =      2.412 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 197392 
    [ 2.500,  3.750) = 197412 
    [ 3.750,  5.000) = 2025 
    [ 5.000,  6.250) = 234 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 56 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.797 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      2.925 ms/op
     p(95.0000) =      3.023 ms/op
     p(99.0000) =      3.514 ms/op
     p(99.9000) =      7.729 ms/op
     p(99.9900) =     13.324 ms/op
     p(99.9990) =     14.635 ms/op
     p(99.9999) =     16.302 ms/op
    p(100.0000) =     16.302 ms/op


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
# Warmup Iteration   1: 4.038 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.611 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.006 ms/op
Iteration   1: 2.479 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.956 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.879 ms/op
                 getUser·p0.999:  11.703 ms/op
                 getUser·p0.9999: 14.321 ms/op
                 getUser·p1.00:   14.631 ms/op

Iteration   2: 2.457 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.863 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.101 ms/op
                 getUser·p0.99:   3.542 ms/op
                 getUser·p0.999:  6.402 ms/op
                 getUser·p0.9999: 13.926 ms/op
                 getUser·p1.00:   14.598 ms/op

Iteration   3: 2.498 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.710 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.994 ms/op
                 getUser·p0.999:  7.832 ms/op
                 getUser·p0.9999: 11.849 ms/op
                 getUser·p1.00:   12.059 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387006
  mean =      2.478 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 91 
    [ 1.250,  2.500) = 193780 
    [ 2.500,  3.750) = 188748 
    [ 3.750,  5.000) = 3525 
    [ 5.000,  6.250) = 389 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 54 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 108 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.710 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.817 ms/op
     p(99.9000) =      7.987 ms/op
     p(99.9900) =     14.121 ms/op
     p(99.9990) =     14.494 ms/op
     p(99.9999) =     14.631 ms/op
    p(100.0000) =     14.631 ms/op


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
# Warmup Iteration   1: 4.703 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.088 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.009 ms/op
Iteration   1: 3.000 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.908 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.388 ms/op
                 listUser·p0.9999: 11.076 ms/op
                 listUser·p1.00:   11.911 ms/op

Iteration   2: 3.009 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.934 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  8.978 ms/op
                 listUser·p0.9999: 13.818 ms/op
                 listUser·p1.00:   14.123 ms/op

Iteration   3: 3.010 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.477 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.710 ms/op
                 listUser·p0.999:  9.241 ms/op
                 listUser·p0.9999: 10.597 ms/op
                 listUser·p1.00:   10.895 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319008
  mean =      3.006 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 157 
    [ 1.250,  2.500) = 95350 
    [ 2.500,  3.750) = 183542 
    [ 3.750,  5.000) = 32503 
    [ 5.000,  6.250) = 6131 
    [ 6.250,  7.500) = 697 
    [ 7.500,  8.750) = 205 
    [ 8.750, 10.000) = 278 
    [10.000, 11.250) = 107 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.477 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =      9.241 ms/op
     p(99.9900) =     12.142 ms/op
     p(99.9990) =     13.969 ms/op
     p(99.9999) =     14.123 ms/op
    p(100.0000) =     14.123 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.661 ± 1.926  ops/ms
ClientPb.existUser                       thrpt       3  13.063 ± 0.895  ops/ms
ClientPb.getUser                         thrpt       3  13.011 ± 0.590  ops/ms
ClientPb.listUser                        thrpt       3  10.860 ± 0.859  ops/ms
ClientPb.createUser                       avgt       3   2.495 ± 0.173   ms/op
ClientPb.existUser                        avgt       3   2.439 ± 0.567   ms/op
ClientPb.getUser                          avgt       3   2.466 ± 0.360   ms/op
ClientPb.listUser                         avgt       3   2.999 ± 0.419   ms/op
ClientPb.createUser                     sample  387191   2.477 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.670           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.531           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.011           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.129           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.727           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.249           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.993           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.872           ms/op
ClientPb.existUser                      sample  397554   2.412 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.797           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.515           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.925           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.514           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.729           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.324           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.302           ms/op
ClientPb.getUser                        sample  387006   2.478 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.710           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.494           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.027           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.817           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.987           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.121           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.631           ms/op
ClientPb.listUser                       sample  319008   3.006 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.477           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.941           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.903           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.603           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.241           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.142           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.123           ms/op
