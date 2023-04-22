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
# Warmup Iteration   1: 0.960 ops/ms
# Warmup Iteration   2: 2.028 ops/ms
# Warmup Iteration   3: 4.556 ops/ms
Iteration   1: 4.910 ops/ms
Iteration   2: 5.216 ops/ms
Iteration   3: 5.207 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.111 ±(99.9%) 3.172 ops/ms [Average]
  (min, avg, max) = (4.910, 5.111, 5.216), stdev = 0.174
  CI (99.9%): [1.939, 8.283] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:17
# Fork: 1 of 1
# Warmup Iteration   1: 1.321 ops/ms
# Warmup Iteration   2: 4.184 ops/ms
# Warmup Iteration   3: 5.423 ops/ms
Iteration   1: 5.455 ops/ms
Iteration   2: 5.377 ops/ms
Iteration   3: 5.592 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.475 ±(99.9%) 1.986 ops/ms [Average]
  (min, avg, max) = (5.377, 5.475, 5.592), stdev = 0.109
  CI (99.9%): [3.488, 7.461] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:09
# Fork: 1 of 1
# Warmup Iteration   1: 1.434 ops/ms
# Warmup Iteration   2: 4.031 ops/ms
# Warmup Iteration   3: 5.233 ops/ms
Iteration   1: 5.082 ops/ms
Iteration   2: 5.127 ops/ms
Iteration   3: 5.240 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.150 ±(99.9%) 1.489 ops/ms [Average]
  (min, avg, max) = (5.082, 5.150, 5.240), stdev = 0.082
  CI (99.9%): [3.661, 6.638] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.327 ops/ms
# Warmup Iteration   2: 3.734 ops/ms
# Warmup Iteration   3: 4.540 ops/ms
Iteration   1: 4.563 ops/ms
Iteration   2: 4.582 ops/ms
Iteration   3: 4.589 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.578 ±(99.9%) 0.247 ops/ms [Average]
  (min, avg, max) = (4.563, 4.578, 4.589), stdev = 0.014
  CI (99.9%): [4.331, 4.825] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:55
# Fork: 1 of 1
# Warmup Iteration   1: 23.742 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 7.686 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.188 ±(99.9%) 0.010 ms/op
Iteration   1: 6.108 ±(99.9%) 0.011 ms/op
Iteration   2: 6.248 ±(99.9%) 0.016 ms/op
Iteration   3: 6.168 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.174 ±(99.9%) 1.278 ms/op [Average]
  (min, avg, max) = (6.108, 6.174, 6.248), stdev = 0.070
  CI (99.9%): [4.896, 7.453] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:48
# Fork: 1 of 1
# Warmup Iteration   1: 18.314 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 7.183 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 6.208 ±(99.9%) 0.011 ms/op
Iteration   1: 6.038 ±(99.9%) 0.013 ms/op
Iteration   2: 5.615 ±(99.9%) 0.016 ms/op
Iteration   3: 5.730 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.794 ±(99.9%) 3.996 ms/op [Average]
  (min, avg, max) = (5.615, 5.794, 6.038), stdev = 0.219
  CI (99.9%): [1.798, 9.790] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:40
# Fork: 1 of 1
# Warmup Iteration   1: 20.206 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 7.719 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.002 ±(99.9%) 0.016 ms/op
Iteration   1: 6.274 ±(99.9%) 0.017 ms/op
Iteration   2: 5.887 ±(99.9%) 0.015 ms/op
Iteration   3: 6.035 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.065 ±(99.9%) 3.562 ms/op [Average]
  (min, avg, max) = (5.887, 6.065, 6.274), stdev = 0.195
  CI (99.9%): [2.503, 9.627] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 20.909 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 8.499 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 7.176 ±(99.9%) 0.014 ms/op
Iteration   1: 6.567 ±(99.9%) 0.019 ms/op
Iteration   2: 7.045 ±(99.9%) 0.012 ms/op
Iteration   3: 6.992 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.868 ±(99.9%) 4.776 ms/op [Average]
  (min, avg, max) = (6.567, 6.868, 7.045), stdev = 0.262
  CI (99.9%): [2.092, 11.644] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 21.707 ±(99.9%) 0.377 ms/op
# Warmup Iteration   2: 8.139 ±(99.9%) 0.065 ms/op
# Warmup Iteration   3: 6.388 ±(99.9%) 0.034 ms/op
Iteration   1: 6.205 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   1.884 ms/op
                 createUser·p0.50:   5.571 ms/op
                 createUser·p0.90:   8.569 ms/op
                 createUser·p0.95:   10.322 ms/op
                 createUser·p0.99:   14.615 ms/op
                 createUser·p0.999:  25.678 ms/op
                 createUser·p0.9999: 36.810 ms/op
                 createUser·p1.00:   37.224 ms/op

Iteration   2: 5.937 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   1.202 ms/op
                 createUser·p0.50:   5.374 ms/op
                 createUser·p0.90:   8.069 ms/op
                 createUser·p0.95:   9.322 ms/op
                 createUser·p0.99:   12.964 ms/op
                 createUser·p0.999:  24.609 ms/op
                 createUser·p0.9999: 29.912 ms/op
                 createUser·p1.00:   30.638 ms/op

Iteration   3: 5.982 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   2.593 ms/op
                 createUser·p0.50:   5.505 ms/op
                 createUser·p0.90:   7.922 ms/op
                 createUser·p0.95:   9.224 ms/op
                 createUser·p0.99:   12.173 ms/op
                 createUser·p0.999:  30.704 ms/op
                 createUser·p0.9999: 43.057 ms/op
                 createUser·p1.00:   51.184 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 158907
  mean =      6.039 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 48418 
    [ 5.000, 10.000) = 104069 
    [10.000, 15.000) = 5527 
    [15.000, 20.000) = 558 
    [20.000, 25.000) = 165 
    [25.000, 30.000) = 75 
    [30.000, 35.000) = 50 
    [35.000, 40.000) = 35 
    [40.000, 45.000) = 8 
    [45.000, 50.000) = 1 
    [50.000, 55.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.202 ms/op
     p(50.0000) =      5.480 ms/op
     p(90.0000) =      8.208 ms/op
     p(95.0000) =      9.568 ms/op
     p(99.0000) =     13.369 ms/op
     p(99.9000) =     25.476 ms/op
     p(99.9900) =     38.280 ms/op
     p(99.9990) =     49.060 ms/op
     p(99.9999) =     51.184 ms/op
    p(100.0000) =     51.184 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 18.651 ±(99.9%) 0.369 ms/op
# Warmup Iteration   2: 7.409 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 5.945 ±(99.9%) 0.035 ms/op
Iteration   1: 5.933 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   2.425 ms/op
                 existUser·p0.50:   5.374 ms/op
                 existUser·p0.90:   8.135 ms/op
                 existUser·p0.95:   9.585 ms/op
                 existUser·p0.99:   13.812 ms/op
                 existUser·p0.999:  24.753 ms/op
                 existUser·p0.9999: 32.017 ms/op
                 existUser·p1.00:   32.932 ms/op

Iteration   2: 5.752 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   2.462 ms/op
                 existUser·p0.50:   5.251 ms/op
                 existUser·p0.90:   7.799 ms/op
                 existUser·p0.95:   9.028 ms/op
                 existUser·p0.99:   12.534 ms/op
                 existUser·p0.999:  20.873 ms/op
                 existUser·p0.9999: 29.801 ms/op
                 existUser·p1.00:   30.704 ms/op

Iteration   3: 5.856 ±(99.9%) 0.030 ms/op
                 existUser·p0.00:   2.417 ms/op
                 existUser·p0.50:   5.243 ms/op
                 existUser·p0.90:   8.110 ms/op
                 existUser·p0.95:   9.748 ms/op
                 existUser·p0.99:   14.156 ms/op
                 existUser·p0.999:  28.836 ms/op
                 existUser·p0.9999: 32.903 ms/op
                 existUser·p1.00:   34.341 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 164187
  mean =      5.846 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 62898 
    [ 5.000,  7.500) = 80452 
    [ 7.500, 10.000) = 14360 
    [10.000, 12.500) = 3918 
    [12.500, 15.000) = 1524 
    [15.000, 17.500) = 596 
    [17.500, 20.000) = 140 
    [20.000, 22.500) = 114 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.417 ms/op
     p(50.0000) =      5.292 ms/op
     p(90.0000) =      8.004 ms/op
     p(95.0000) =      9.454 ms/op
     p(99.0000) =     13.582 ms/op
     p(99.9000) =     24.478 ms/op
     p(99.9900) =     31.692 ms/op
     p(99.9990) =     33.794 ms/op
     p(99.9999) =     34.341 ms/op
    p(100.0000) =     34.341 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 21.710 ±(99.9%) 0.357 ms/op
# Warmup Iteration   2: 8.760 ±(99.9%) 0.079 ms/op
# Warmup Iteration   3: 6.730 ±(99.9%) 0.042 ms/op
Iteration   1: 6.451 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   1.647 ms/op
                 getUser·p0.50:   5.833 ms/op
                 getUser·p0.90:   9.028 ms/op
                 getUser·p0.95:   10.777 ms/op
                 getUser·p0.99:   14.587 ms/op
                 getUser·p0.999:  25.555 ms/op
                 getUser·p0.9999: 32.276 ms/op
                 getUser·p1.00:   32.276 ms/op

Iteration   2: 6.394 ±(99.9%) 0.033 ms/op
                 getUser·p0.00:   1.552 ms/op
                 getUser·p0.50:   5.693 ms/op
                 getUser·p0.90:   9.060 ms/op
                 getUser·p0.95:   10.797 ms/op
                 getUser·p0.99:   14.582 ms/op
                 getUser·p0.999:  24.966 ms/op
                 getUser·p0.9999: 29.655 ms/op
                 getUser·p1.00:   31.457 ms/op

Iteration   3: 6.205 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   2.470 ms/op
                 getUser·p0.50:   5.644 ms/op
                 getUser·p0.90:   8.520 ms/op
                 getUser·p0.95:   10.207 ms/op
                 getUser·p0.99:   14.008 ms/op
                 getUser·p0.999:  29.079 ms/op
                 getUser·p0.9999: 31.709 ms/op
                 getUser·p1.00:   32.276 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 151239
  mean =      6.348 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 32447 
    [ 5.000,  7.500) = 91902 
    [ 7.500, 10.000) = 17341 
    [10.000, 12.500) = 6081 
    [12.500, 15.000) = 2300 
    [15.000, 17.500) = 717 
    [17.500, 20.000) = 146 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 70 
    [30.000, 32.500) = 45 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.552 ms/op
     p(50.0000) =      5.718 ms/op
     p(90.0000) =      8.880 ms/op
     p(95.0000) =     10.584 ms/op
     p(99.0000) =     14.402 ms/op
     p(99.9000) =     25.854 ms/op
     p(99.9900) =     31.519 ms/op
     p(99.9990) =     32.276 ms/op
     p(99.9999) =     32.276 ms/op
    p(100.0000) =     32.276 ms/op


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
# Warmup Iteration   1: 23.443 ±(99.9%) 0.463 ms/op
# Warmup Iteration   2: 9.488 ±(99.9%) 0.092 ms/op
# Warmup Iteration   3: 7.558 ±(99.9%) 0.044 ms/op
Iteration   1: 7.049 ±(99.9%) 0.037 ms/op
                 listUser·p0.00:   3.097 ms/op
                 listUser·p0.50:   6.341 ms/op
                 listUser·p0.90:   9.716 ms/op
                 listUser·p0.95:   11.567 ms/op
                 listUser·p0.99:   15.987 ms/op
                 listUser·p0.999:  31.431 ms/op
                 listUser·p0.9999: 35.878 ms/op
                 listUser·p1.00:   36.700 ms/op

Iteration   2: 7.239 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   2.294 ms/op
                 listUser·p0.50:   6.496 ms/op
                 listUser·p0.90:   10.060 ms/op
                 listUser·p0.95:   11.796 ms/op
                 listUser·p0.99:   16.613 ms/op
                 listUser·p0.999:  29.704 ms/op
                 listUser·p0.9999: 35.067 ms/op
                 listUser·p1.00:   36.241 ms/op

Iteration   3: 6.910 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   3.334 ms/op
                 listUser·p0.50:   6.283 ms/op
                 listUser·p0.90:   9.110 ms/op
                 listUser·p0.95:   11.092 ms/op
                 listUser·p0.99:   15.466 ms/op
                 listUser·p0.999:  33.142 ms/op
                 listUser·p0.9999: 36.118 ms/op
                 listUser·p1.00:   38.339 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 135871
  mean =      7.064 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 3878 
    [ 5.000,  7.500) = 99366 
    [ 7.500, 10.000) = 20781 
    [10.000, 12.500) = 7400 
    [12.500, 15.000) = 2643 
    [15.000, 17.500) = 927 
    [17.500, 20.000) = 301 
    [20.000, 22.500) = 151 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 99 
    [30.000, 32.500) = 71 
    [32.500, 35.000) = 75 
    [35.000, 37.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      2.294 ms/op
     p(50.0000) =      6.373 ms/op
     p(90.0000) =      9.617 ms/op
     p(95.0000) =     11.518 ms/op
     p(99.0000) =     16.007 ms/op
     p(99.9000) =     31.167 ms/op
     p(99.9900) =     35.783 ms/op
     p(99.9990) =     37.915 ms/op
     p(99.9999) =     38.339 ms/op
    p(100.0000) =     38.339 ms/op


# Run complete. Total time: 00:13:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.111 ± 3.172  ops/ms
ClientPb.existUser                       thrpt       3   5.475 ± 1.986  ops/ms
ClientPb.getUser                         thrpt       3   5.150 ± 1.489  ops/ms
ClientPb.listUser                        thrpt       3   4.578 ± 0.247  ops/ms
ClientPb.createUser                       avgt       3   6.174 ± 1.278   ms/op
ClientPb.existUser                        avgt       3   5.794 ± 3.996   ms/op
ClientPb.getUser                          avgt       3   6.065 ± 3.562   ms/op
ClientPb.listUser                         avgt       3   6.868 ± 4.776   ms/op
ClientPb.createUser                     sample  158907   6.039 ± 0.017   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.202           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.480           ms/op
ClientPb.createUser:createUser·p0.90    sample           8.208           ms/op
ClientPb.createUser:createUser·p0.95    sample           9.568           ms/op
ClientPb.createUser:createUser·p0.99    sample          13.369           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.476           ms/op
ClientPb.createUser:createUser·p0.9999  sample          38.280           ms/op
ClientPb.createUser:createUser·p1.00    sample          51.184           ms/op
ClientPb.existUser                      sample  164187   5.846 ± 0.016   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.417           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.292           ms/op
ClientPb.existUser:existUser·p0.90      sample           8.004           ms/op
ClientPb.existUser:existUser·p0.95      sample           9.454           ms/op
ClientPb.existUser:existUser·p0.99      sample          13.582           ms/op
ClientPb.existUser:existUser·p0.999     sample          24.478           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.692           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.341           ms/op
ClientPb.getUser                        sample  151239   6.348 ± 0.018   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.552           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.718           ms/op
ClientPb.getUser:getUser·p0.90          sample           8.880           ms/op
ClientPb.getUser:getUser·p0.95          sample          10.584           ms/op
ClientPb.getUser:getUser·p0.99          sample          14.402           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.854           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.519           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.276           ms/op
ClientPb.listUser                       sample  135871   7.064 ± 0.021   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.294           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.373           ms/op
ClientPb.listUser:listUser·p0.90        sample           9.617           ms/op
ClientPb.listUser:listUser·p0.95        sample          11.518           ms/op
ClientPb.listUser:listUser·p0.99        sample          16.007           ms/op
ClientPb.listUser:listUser·p0.999       sample          31.167           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.783           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.339           ms/op
