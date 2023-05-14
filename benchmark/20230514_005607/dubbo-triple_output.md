# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.889 ops/ms
# Warmup Iteration   2: 5.359 ops/ms
# Warmup Iteration   3: 8.433 ops/ms
Iteration   1: 9.241 ops/ms
Iteration   2: 9.468 ops/ms
Iteration   3: 8.833 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.181 ±(99.9%) 5.867 ops/ms [Average]
  (min, avg, max) = (8.833, 9.181, 9.468), stdev = 0.322
  CI (99.9%): [3.314, 15.047] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.862 ops/ms
# Warmup Iteration   2: 8.484 ops/ms
# Warmup Iteration   3: 9.366 ops/ms
Iteration   1: 9.578 ops/ms
Iteration   2: 9.406 ops/ms
Iteration   3: 9.594 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.526 ±(99.9%) 1.896 ops/ms [Average]
  (min, avg, max) = (9.406, 9.526, 9.594), stdev = 0.104
  CI (99.9%): [7.630, 11.422] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.907 ops/ms
# Warmup Iteration   2: 7.880 ops/ms
# Warmup Iteration   3: 8.659 ops/ms
Iteration   1: 9.229 ops/ms
Iteration   2: 9.222 ops/ms
Iteration   3: 9.445 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.299 ±(99.9%) 2.314 ops/ms [Average]
  (min, avg, max) = (9.222, 9.299, 9.445), stdev = 0.127
  CI (99.9%): [6.985, 11.613] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.789 ops/ms
# Warmup Iteration   2: 6.376 ops/ms
# Warmup Iteration   3: 7.662 ops/ms
Iteration   1: 7.998 ops/ms
Iteration   2: 8.041 ops/ms
Iteration   3: 8.163 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.067 ±(99.9%) 1.559 ops/ms [Average]
  (min, avg, max) = (7.998, 8.067, 8.163), stdev = 0.085
  CI (99.9%): [6.508, 9.626] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 11.116 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.771 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.563 ±(99.9%) 0.004 ms/op
Iteration   1: 3.360 ±(99.9%) 0.010 ms/op
Iteration   2: 3.551 ±(99.9%) 0.007 ms/op
Iteration   3: 3.357 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.423 ±(99.9%) 2.028 ms/op [Average]
  (min, avg, max) = (3.357, 3.423, 3.551), stdev = 0.111
  CI (99.9%): [1.395, 5.450] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 8.733 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.545 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.314 ±(99.9%) 0.005 ms/op
Iteration   1: 3.332 ±(99.9%) 0.004 ms/op
Iteration   2: 3.225 ±(99.9%) 0.006 ms/op
Iteration   3: 3.252 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.270 ±(99.9%) 1.020 ms/op [Average]
  (min, avg, max) = (3.225, 3.270, 3.332), stdev = 0.056
  CI (99.9%): [2.250, 4.289] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 10.598 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.730 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.533 ±(99.9%) 0.003 ms/op
Iteration   1: 3.493 ±(99.9%) 0.004 ms/op
Iteration   2: 3.322 ±(99.9%) 0.005 ms/op
Iteration   3: 3.332 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.383 ±(99.9%) 1.755 ms/op [Average]
  (min, avg, max) = (3.322, 3.383, 3.493), stdev = 0.096
  CI (99.9%): [1.628, 5.137] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.322 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.454 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.029 ±(99.9%) 0.012 ms/op
Iteration   1: 3.944 ±(99.9%) 0.012 ms/op
Iteration   2: 3.998 ±(99.9%) 0.008 ms/op
Iteration   3: 3.914 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.952 ±(99.9%) 0.774 ms/op [Average]
  (min, avg, max) = (3.914, 3.952, 3.998), stdev = 0.042
  CI (99.9%): [3.178, 4.726] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 9.338 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.866 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.420 ±(99.9%) 0.010 ms/op
Iteration   1: 3.386 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.389 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.850 ms/op
                 createUser·p0.95:   4.178 ms/op
                 createUser·p0.99:   5.865 ms/op
                 createUser·p0.999:  20.025 ms/op
                 createUser·p0.9999: 23.680 ms/op
                 createUser·p1.00:   24.281 ms/op

Iteration   2: 3.386 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.364 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   6.087 ms/op
                 createUser·p0.999:  21.259 ms/op
                 createUser·p0.9999: 29.890 ms/op
                 createUser·p1.00:   31.064 ms/op

Iteration   3: 3.497 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.452 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   4.116 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   6.046 ms/op
                 createUser·p0.999:  20.190 ms/op
                 createUser·p0.9999: 32.698 ms/op
                 createUser·p1.00:   34.275 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280417
  mean =      3.422 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8302 
    [ 2.500,  5.000) = 265536 
    [ 5.000,  7.500) = 5465 
    [ 7.500, 10.000) = 682 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.364 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =     20.152 ms/op
     p(99.9900) =     31.261 ms/op
     p(99.9990) =     34.210 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 10.299 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.697 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.507 ±(99.9%) 0.010 ms/op
Iteration   1: 3.411 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.266 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.883 ms/op
                 existUser·p0.95:   4.375 ms/op
                 existUser·p0.99:   6.054 ms/op
                 existUser·p0.999:  20.793 ms/op
                 existUser·p0.9999: 23.953 ms/op
                 existUser·p1.00:   24.347 ms/op

Iteration   2: 3.230 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.436 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   5.726 ms/op
                 existUser·p0.999:  9.880 ms/op
                 existUser·p0.9999: 25.728 ms/op
                 existUser·p1.00:   27.001 ms/op

Iteration   3: 3.253 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.698 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   5.169 ms/op
                 existUser·p0.999:  17.137 ms/op
                 existUser·p0.9999: 26.345 ms/op
                 existUser·p1.00:   28.705 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 291135
  mean =      3.296 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12958 
    [ 2.500,  5.000) = 272443 
    [ 5.000,  7.500) = 4693 
    [ 7.500, 10.000) = 488 
    [10.000, 12.500) = 214 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 134 
    [25.000, 27.500) = 78 

  Percentiles, ms/op:
      p(0.0000) =      1.266 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     13.500 ms/op
     p(99.9900) =     25.981 ms/op
     p(99.9990) =     27.001 ms/op
     p(99.9999) =     28.705 ms/op
    p(100.0000) =     28.705 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 10.443 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 3.911 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.653 ±(99.9%) 0.011 ms/op
Iteration   1: 3.440 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.739 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   6.808 ms/op
                 getUser·p0.999:  20.474 ms/op
                 getUser·p0.9999: 25.418 ms/op
                 getUser·p1.00:   26.214 ms/op

Iteration   2: 3.517 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.374 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   4.170 ms/op
                 getUser·p0.95:   4.792 ms/op
                 getUser·p0.99:   6.447 ms/op
                 getUser·p0.999:  24.082 ms/op
                 getUser·p0.9999: 29.881 ms/op
                 getUser·p1.00:   30.769 ms/op

Iteration   3: 3.332 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.817 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   6.095 ms/op
                 getUser·p0.999:  18.529 ms/op
                 getUser·p0.9999: 27.689 ms/op
                 getUser·p1.00:   28.443 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280141
  mean =      3.428 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2179 
    [ 2.500,  5.000) = 269430 
    [ 5.000,  7.500) = 7048 
    [ 7.500, 10.000) = 908 
    [10.000, 12.500) = 239 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.374 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      6.365 ms/op
     p(99.9000) =     20.283 ms/op
     p(99.9900) =     28.671 ms/op
     p(99.9990) =     30.428 ms/op
     p(99.9999) =     30.769 ms/op
    p(100.0000) =     30.769 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.832 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.556 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.088 ±(99.9%) 0.013 ms/op
Iteration   1: 3.925 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.802 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  17.744 ms/op
                 listUser·p0.9999: 33.320 ms/op
                 listUser·p1.00:   34.603 ms/op

Iteration   2: 4.003 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.404 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.874 ms/op
                 listUser·p0.99:   7.422 ms/op
                 listUser·p0.999:  16.043 ms/op
                 listUser·p0.9999: 18.448 ms/op
                 listUser·p1.00:   20.873 ms/op

Iteration   3: 3.936 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.563 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  14.631 ms/op
                 listUser·p0.9999: 17.203 ms/op
                 listUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242549
  mean =      3.954 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26 
    [ 2.500,  5.000) = 235499 
    [ 5.000,  7.500) = 5225 
    [ 7.500, 10.000) = 1013 
    [10.000, 12.500) = 224 
    [12.500, 15.000) = 213 
    [15.000, 17.500) = 244 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.563 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     15.736 ms/op
     p(99.9900) =     32.080 ms/op
     p(99.9990) =     33.977 ms/op
     p(99.9999) =     34.603 ms/op
    p(100.0000) =     34.603 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.181 ± 5.867  ops/ms
ClientPb.existUser                       thrpt       3   9.526 ± 1.896  ops/ms
ClientPb.getUser                         thrpt       3   9.299 ± 2.314  ops/ms
ClientPb.listUser                        thrpt       3   8.067 ± 1.559  ops/ms
ClientPb.createUser                       avgt       3   3.423 ± 2.028   ms/op
ClientPb.existUser                        avgt       3   3.270 ± 1.020   ms/op
ClientPb.getUser                          avgt       3   3.383 ± 1.755   ms/op
ClientPb.listUser                         avgt       3   3.952 ± 0.774   ms/op
ClientPb.createUser                     sample  280417   3.422 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.364           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.305           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.920           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.260           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.005           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.152           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.261           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.275           ms/op
ClientPb.existUser                      sample  291135   3.296 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.266           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.219           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.621           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.949           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.726           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.500           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.981           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.705           ms/op
ClientPb.getUser                        sample  280141   3.428 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.374           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.256           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.817           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.350           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.365           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.283           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.671           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.769           ms/op
ClientPb.listUser                       sample  242549   3.954 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.563           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.838           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.612           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.053           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.736           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.080           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.603           ms/op
