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
# Warmup Iteration   1: 5.000 ops/ms
# Warmup Iteration   2: 12.122 ops/ms
# Warmup Iteration   3: 12.212 ops/ms
Iteration   1: 12.569 ops/ms
Iteration   2: 12.695 ops/ms
Iteration   3: 12.735 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.666 ±(99.9%) 1.582 ops/ms [Average]
  (min, avg, max) = (12.569, 12.666, 12.735), stdev = 0.087
  CI (99.9%): [11.084, 14.248] (assumes normal distribution)


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
# Warmup Iteration   1: 8.242 ops/ms
# Warmup Iteration   2: 12.976 ops/ms
# Warmup Iteration   3: 13.069 ops/ms
Iteration   1: 13.258 ops/ms
Iteration   2: 13.040 ops/ms
Iteration   3: 13.081 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.126 ±(99.9%) 2.105 ops/ms [Average]
  (min, avg, max) = (13.040, 13.126, 13.258), stdev = 0.115
  CI (99.9%): [11.022, 15.231] (assumes normal distribution)


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
# Warmup Iteration   1: 8.131 ops/ms
# Warmup Iteration   2: 12.856 ops/ms
# Warmup Iteration   3: 12.963 ops/ms
Iteration   1: 13.172 ops/ms
Iteration   2: 13.105 ops/ms
Iteration   3: 13.181 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.153 ±(99.9%) 0.752 ops/ms [Average]
  (min, avg, max) = (13.105, 13.153, 13.181), stdev = 0.041
  CI (99.9%): [12.401, 13.905] (assumes normal distribution)


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
# Warmup Iteration   1: 6.864 ops/ms
# Warmup Iteration   2: 10.568 ops/ms
# Warmup Iteration   3: 10.813 ops/ms
Iteration   1: 10.756 ops/ms
Iteration   2: 10.841 ops/ms
Iteration   3: 10.766 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.788 ±(99.9%) 0.848 ops/ms [Average]
  (min, avg, max) = (10.756, 10.788, 10.841), stdev = 0.046
  CI (99.9%): [9.940, 11.636] (assumes normal distribution)


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
# Warmup Iteration   1: 3.982 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.554 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.480 ±(99.9%) 0.004 ms/op
Iteration   1: 2.510 ±(99.9%) 0.004 ms/op
Iteration   2: 2.501 ±(99.9%) 0.004 ms/op
Iteration   3: 2.504 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.505 ±(99.9%) 0.085 ms/op [Average]
  (min, avg, max) = (2.501, 2.505, 2.510), stdev = 0.005
  CI (99.9%): [2.420, 2.590] (assumes normal distribution)


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
# Warmup Iteration   1: 3.496 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.403 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.447 ±(99.9%) 0.004 ms/op
Iteration   1: 2.441 ±(99.9%) 0.003 ms/op
Iteration   2: 2.422 ±(99.9%) 0.003 ms/op
Iteration   3: 2.456 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.440 ±(99.9%) 0.312 ms/op [Average]
  (min, avg, max) = (2.422, 2.440, 2.456), stdev = 0.017
  CI (99.9%): [2.128, 2.752] (assumes normal distribution)


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
# Warmup Iteration   1: 3.984 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.524 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.469 ±(99.9%) 0.004 ms/op
Iteration   1: 2.488 ±(99.9%) 0.004 ms/op
Iteration   2: 2.435 ±(99.9%) 0.003 ms/op
Iteration   3: 2.449 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.457 ±(99.9%) 0.504 ms/op [Average]
  (min, avg, max) = (2.435, 2.457, 2.488), stdev = 0.028
  CI (99.9%): [1.953, 2.961] (assumes normal distribution)


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
# Warmup Iteration   1: 4.515 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.005 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.005 ms/op
Iteration   1: 2.962 ±(99.9%) 0.005 ms/op
Iteration   2: 2.973 ±(99.9%) 0.004 ms/op
Iteration   3: 2.958 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.965 ±(99.9%) 0.147 ms/op [Average]
  (min, avg, max) = (2.958, 2.965, 2.973), stdev = 0.008
  CI (99.9%): [2.818, 3.111] (assumes normal distribution)


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
# Warmup Iteration   1: 4.059 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.633 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.488 ±(99.9%) 0.006 ms/op
Iteration   1: 2.466 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.817 ms/op
                 createUser·p0.50:   2.519 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.649 ms/op
                 createUser·p0.999:  6.546 ms/op
                 createUser·p0.9999: 13.337 ms/op
                 createUser·p1.00:   13.435 ms/op

Iteration   2: 2.481 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.727 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.740 ms/op
                 createUser·p0.999:  7.732 ms/op
                 createUser·p0.9999: 11.990 ms/op
                 createUser·p1.00:   13.042 ms/op

Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.904 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.842 ms/op
                 createUser·p0.999:  8.902 ms/op
                 createUser·p0.9999: 10.692 ms/op
                 createUser·p1.00:   14.467 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386562
  mean =      2.481 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 189519 
    [ 2.500,  3.750) = 193105 
    [ 3.750,  5.000) = 3133 
    [ 5.000,  6.250) = 303 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 127 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.727 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.752 ms/op
     p(99.9000) =      8.614 ms/op
     p(99.9900) =     13.031 ms/op
     p(99.9990) =     13.435 ms/op
     p(99.9999) =     14.467 ms/op
    p(100.0000) =     14.467 ms/op


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
# Warmup Iteration   1: 3.692 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.460 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.437 ±(99.9%) 0.005 ms/op
Iteration   1: 2.431 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.912 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.482 ms/op
                 existUser·p0.999:  5.812 ms/op
                 existUser·p0.9999: 16.187 ms/op
                 existUser·p1.00:   16.482 ms/op

Iteration   2: 2.442 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.961 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.555 ms/op
                 existUser·p0.999:  7.369 ms/op
                 existUser·p0.9999: 12.354 ms/op
                 existUser·p1.00:   13.861 ms/op

Iteration   3: 2.436 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.984 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.629 ms/op
                 existUser·p0.999:  7.364 ms/op
                 existUser·p0.9999: 12.151 ms/op
                 existUser·p1.00:   12.501 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393706
  mean =      2.436 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 198741 
    [ 2.500,  3.750) = 192150 
    [ 3.750,  5.000) = 2165 
    [ 5.000,  6.250) = 199 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.912 ms/op
     p(50.0000) =      2.482 ms/op
     p(90.0000) =      2.961 ms/op
     p(95.0000) =      3.064 ms/op
     p(99.0000) =      3.559 ms/op
     p(99.9000) =      7.144 ms/op
     p(99.9900) =     13.576 ms/op
     p(99.9990) =     16.322 ms/op
     p(99.9999) =     16.482 ms/op
    p(100.0000) =     16.482 ms/op


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
# Warmup Iteration   1: 3.868 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.588 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.519 ±(99.9%) 0.006 ms/op
Iteration   1: 2.482 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.906 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.596 ms/op
                 getUser·p0.999:  9.131 ms/op
                 getUser·p0.9999: 13.373 ms/op
                 getUser·p1.00:   13.812 ms/op

Iteration   2: 2.533 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.984 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   4.010 ms/op
                 getUser·p0.999:  9.355 ms/op
                 getUser·p0.9999: 11.967 ms/op
                 getUser·p1.00:   12.435 ms/op

Iteration   3: 2.509 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.928 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.867 ms/op
                 getUser·p0.999:  8.332 ms/op
                 getUser·p0.9999: 10.937 ms/op
                 getUser·p1.00:   12.272 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382420
  mean =      2.508 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 188874 
    [ 2.500,  3.750) = 189073 
    [ 3.750,  5.000) = 3587 
    [ 5.000,  6.250) = 401 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 113 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.906 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.834 ms/op
     p(99.9000) =      8.611 ms/op
     p(99.9900) =     12.878 ms/op
     p(99.9990) =     13.561 ms/op
     p(99.9999) =     13.812 ms/op
    p(100.0000) =     13.812 ms/op


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
# Warmup Iteration   1: 4.776 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.056 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.009 ms/op
Iteration   1: 3.046 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.912 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   5.775 ms/op
                 listUser·p0.999:  9.929 ms/op
                 listUser·p0.9999: 12.542 ms/op
                 listUser·p1.00:   13.107 ms/op

Iteration   2: 3.028 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.900 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  9.477 ms/op
                 listUser·p0.9999: 11.116 ms/op
                 listUser·p1.00:   11.878 ms/op

Iteration   3: 3.003 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.646 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  10.216 ms/op
                 listUser·p0.9999: 12.794 ms/op
                 listUser·p1.00:   14.959 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317021
  mean =      3.026 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 131 
    [ 1.250,  2.500) = 89035 
    [ 2.500,  3.750) = 187979 
    [ 3.750,  5.000) = 32286 
    [ 5.000,  6.250) = 6276 
    [ 6.250,  7.500) = 669 
    [ 7.500,  8.750) = 143 
    [ 8.750, 10.000) = 205 
    [10.000, 11.250) = 200 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.646 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =      9.912 ms/op
     p(99.9900) =     12.335 ms/op
     p(99.9990) =     14.726 ms/op
     p(99.9999) =     14.959 ms/op
    p(100.0000) =     14.959 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.666 ± 1.582  ops/ms
ClientPb.existUser                       thrpt       3  13.126 ± 2.105  ops/ms
ClientPb.getUser                         thrpt       3  13.153 ± 0.752  ops/ms
ClientPb.listUser                        thrpt       3  10.788 ± 0.848  ops/ms
ClientPb.createUser                       avgt       3   2.505 ± 0.085   ms/op
ClientPb.existUser                        avgt       3   2.440 ± 0.312   ms/op
ClientPb.getUser                          avgt       3   2.457 ± 0.504   ms/op
ClientPb.listUser                         avgt       3   2.965 ± 0.147   ms/op
ClientPb.createUser                     sample  386562   2.481 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.727           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.535           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.019           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.752           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.614           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.031           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.467           ms/op
ClientPb.existUser                      sample  393706   2.436 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.912           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.482           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.961           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.064           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.559           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.144           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.576           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.482           ms/op
ClientPb.getUser                        sample  382420   2.508 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.906           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.535           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.834           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.611           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.878           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.812           ms/op
ClientPb.listUser                       sample  317021   3.026 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.646           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.669           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.912           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.335           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.959           ms/op
