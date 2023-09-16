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
# Warmup Iteration   1: 1.069 ops/ms
# Warmup Iteration   2: 2.328 ops/ms
# Warmup Iteration   3: 4.764 ops/ms
Iteration   1: 5.561 ops/ms
Iteration   2: 5.498 ops/ms
Iteration   3: 5.330 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.463 ±(99.9%) 2.174 ops/ms [Average]
  (min, avg, max) = (5.330, 5.463, 5.561), stdev = 0.119
  CI (99.9%): [3.289, 7.637] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:17
# Fork: 1 of 1
# Warmup Iteration   1: 1.522 ops/ms
# Warmup Iteration   2: 3.877 ops/ms
# Warmup Iteration   3: 5.297 ops/ms
Iteration   1: 5.387 ops/ms
Iteration   2: 5.650 ops/ms
Iteration   3: 5.812 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.616 ±(99.9%) 3.911 ops/ms [Average]
  (min, avg, max) = (5.387, 5.616, 5.812), stdev = 0.214
  CI (99.9%): [1.705, 9.527] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.356 ops/ms
# Warmup Iteration   2: 3.958 ops/ms
# Warmup Iteration   3: 5.275 ops/ms
Iteration   1: 4.989 ops/ms
Iteration   2: 5.054 ops/ms
Iteration   3: 5.158 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.067 ±(99.9%) 1.562 ops/ms [Average]
  (min, avg, max) = (4.989, 5.067, 5.158), stdev = 0.086
  CI (99.9%): [3.505, 6.629] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.256 ops/ms
# Warmup Iteration   2: 3.190 ops/ms
# Warmup Iteration   3: 4.562 ops/ms
Iteration   1: 4.779 ops/ms
Iteration   2: 4.890 ops/ms
Iteration   3: 4.751 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.806 ±(99.9%) 1.337 ops/ms [Average]
  (min, avg, max) = (4.751, 4.806, 4.890), stdev = 0.073
  CI (99.9%): [3.469, 6.144] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 21.787 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 8.270 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 6.340 ±(99.9%) 0.011 ms/op
Iteration   1: 6.222 ±(99.9%) 0.014 ms/op
Iteration   2: 6.292 ±(99.9%) 0.012 ms/op
Iteration   3: 5.937 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.151 ±(99.9%) 3.430 ms/op [Average]
  (min, avg, max) = (5.937, 6.151, 6.292), stdev = 0.188
  CI (99.9%): [2.721, 9.580] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 20.237 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 6.991 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.648 ±(99.9%) 0.008 ms/op
Iteration   1: 5.788 ±(99.9%) 0.009 ms/op
Iteration   2: 5.672 ±(99.9%) 0.009 ms/op
Iteration   3: 5.553 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.671 ±(99.9%) 2.143 ms/op [Average]
  (min, avg, max) = (5.553, 5.671, 5.788), stdev = 0.117
  CI (99.9%): [3.528, 7.814] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 22.264 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 7.520 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.839 ±(99.9%) 0.009 ms/op
Iteration   1: 6.360 ±(99.9%) 0.009 ms/op
Iteration   2: 6.175 ±(99.9%) 0.010 ms/op
Iteration   3: 5.921 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.152 ±(99.9%) 4.026 ms/op [Average]
  (min, avg, max) = (5.921, 6.152, 6.360), stdev = 0.221
  CI (99.9%): [2.126, 10.178] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 22.293 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 8.130 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 7.121 ±(99.9%) 0.014 ms/op
Iteration   1: 7.164 ±(99.9%) 0.011 ms/op
Iteration   2: 7.203 ±(99.9%) 0.013 ms/op
Iteration   3: 6.961 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.109 ±(99.9%) 2.367 ms/op [Average]
  (min, avg, max) = (6.961, 7.109, 7.203), stdev = 0.130
  CI (99.9%): [4.742, 9.477] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 19.509 ±(99.9%) 0.458 ms/op
# Warmup Iteration   2: 8.980 ±(99.9%) 0.076 ms/op
# Warmup Iteration   3: 6.841 ±(99.9%) 0.040 ms/op
Iteration   1: 6.136 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   1.958 ms/op
                 createUser·p0.50:   5.603 ms/op
                 createUser·p0.90:   7.799 ms/op
                 createUser·p0.95:   9.421 ms/op
                 createUser·p0.99:   13.484 ms/op
                 createUser·p0.999:  32.983 ms/op
                 createUser·p0.9999: 37.473 ms/op
                 createUser·p1.00:   38.535 ms/op

Iteration   2: 5.973 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.007 ms/op
                 createUser·p0.50:   5.628 ms/op
                 createUser·p0.90:   7.422 ms/op
                 createUser·p0.95:   8.389 ms/op
                 createUser·p0.99:   11.600 ms/op
                 createUser·p0.999:  30.153 ms/op
                 createUser·p0.9999: 34.406 ms/op
                 createUser·p1.00:   34.800 ms/op

Iteration   3: 6.075 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   2.789 ms/op
                 createUser·p0.50:   5.726 ms/op
                 createUser·p0.90:   7.496 ms/op
                 createUser·p0.95:   8.454 ms/op
                 createUser·p0.99:   12.239 ms/op
                 createUser·p0.999:  30.747 ms/op
                 createUser·p0.9999: 38.566 ms/op
                 createUser·p1.00:   39.059 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 158406
  mean =      6.061 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 25572 
    [ 5.000,  7.500) = 116279 
    [ 7.500, 10.000) = 12309 
    [10.000, 12.500) = 2705 
    [12.500, 15.000) = 867 
    [15.000, 17.500) = 306 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 76 
    [32.500, 35.000) = 67 
    [35.000, 37.500) = 44 

  Percentiles, ms/op:
      p(0.0000) =      1.958 ms/op
     p(50.0000) =      5.652 ms/op
     p(90.0000) =      7.561 ms/op
     p(95.0000) =      8.733 ms/op
     p(99.0000) =     12.419 ms/op
     p(99.9000) =     31.392 ms/op
     p(99.9900) =     37.487 ms/op
     p(99.9990) =     38.983 ms/op
     p(99.9999) =     39.059 ms/op
    p(100.0000) =     39.059 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 19.910 ±(99.9%) 0.352 ms/op
# Warmup Iteration   2: 7.135 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 6.059 ±(99.9%) 0.027 ms/op
Iteration   1: 5.700 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.695 ms/op
                 existUser·p0.50:   5.251 ms/op
                 existUser·p0.90:   7.348 ms/op
                 existUser·p0.95:   8.798 ms/op
                 existUser·p0.99:   11.387 ms/op
                 existUser·p0.999:  18.704 ms/op
                 existUser·p0.9999: 31.654 ms/op
                 existUser·p1.00:   31.850 ms/op

Iteration   2: 5.784 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.444 ms/op
                 existUser·p0.50:   5.317 ms/op
                 existUser·p0.90:   7.438 ms/op
                 existUser·p0.95:   8.700 ms/op
                 existUser·p0.99:   12.681 ms/op
                 existUser·p0.999:  30.919 ms/op
                 existUser·p0.9999: 42.819 ms/op
                 existUser·p1.00:   47.120 ms/op

Iteration   3: 5.625 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.376 ms/op
                 existUser·p0.50:   5.243 ms/op
                 existUser·p0.90:   7.078 ms/op
                 existUser·p0.95:   8.184 ms/op
                 existUser·p0.99:   11.305 ms/op
                 existUser·p0.999:  21.369 ms/op
                 existUser·p0.9999: 30.372 ms/op
                 existUser·p1.00:   30.736 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 168307
  mean =      5.702 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 56479 
    [ 5.000, 10.000) = 107598 
    [10.000, 15.000) = 3706 
    [15.000, 20.000) = 364 
    [20.000, 25.000) = 32 
    [25.000, 30.000) = 44 
    [30.000, 35.000) = 56 
    [35.000, 40.000) = 15 
    [40.000, 45.000) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.444 ms/op
     p(50.0000) =      5.267 ms/op
     p(90.0000) =      7.266 ms/op
     p(95.0000) =      8.552 ms/op
     p(99.0000) =     11.862 ms/op
     p(99.9000) =     19.792 ms/op
     p(99.9900) =     39.191 ms/op
     p(99.9990) =     45.016 ms/op
     p(99.9999) =     47.120 ms/op
    p(100.0000) =     47.120 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 19.084 ±(99.9%) 0.322 ms/op
# Warmup Iteration   2: 8.363 ±(99.9%) 0.070 ms/op
# Warmup Iteration   3: 6.101 ±(99.9%) 0.026 ms/op
Iteration   1: 5.880 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.515 ms/op
                 getUser·p0.50:   5.415 ms/op
                 getUser·p0.90:   7.537 ms/op
                 getUser·p0.95:   9.028 ms/op
                 getUser·p0.99:   12.567 ms/op
                 getUser·p0.999:  19.428 ms/op
                 getUser·p0.9999: 35.463 ms/op
                 getUser·p1.00:   35.979 ms/op

Iteration   2: 5.853 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.224 ms/op
                 getUser·p0.50:   5.456 ms/op
                 getUser·p0.90:   7.430 ms/op
                 getUser·p0.95:   8.798 ms/op
                 getUser·p0.99:   12.403 ms/op
                 getUser·p0.999:  25.887 ms/op
                 getUser·p0.9999: 31.802 ms/op
                 getUser·p1.00:   32.506 ms/op

Iteration   3: 5.770 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.305 ms/op
                 getUser·p0.50:   5.513 ms/op
                 getUser·p0.90:   6.947 ms/op
                 getUser·p0.95:   7.889 ms/op
                 getUser·p0.99:   10.912 ms/op
                 getUser·p0.999:  31.162 ms/op
                 getUser·p0.9999: 34.240 ms/op
                 getUser·p1.00:   35.783 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 164537
  mean =      5.834 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 41078 
    [ 5.000,  7.500) = 109012 
    [ 7.500, 10.000) = 10462 
    [10.000, 12.500) = 2662 
    [12.500, 15.000) = 757 
    [15.000, 17.500) = 299 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 73 
    [32.500, 35.000) = 33 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.305 ms/op
     p(50.0000) =      5.464 ms/op
     p(90.0000) =      7.283 ms/op
     p(95.0000) =      8.552 ms/op
     p(99.0000) =     11.993 ms/op
     p(99.9000) =     21.430 ms/op
     p(99.9900) =     34.275 ms/op
     p(99.9990) =     35.895 ms/op
     p(99.9999) =     35.979 ms/op
    p(100.0000) =     35.979 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 22.087 ±(99.9%) 0.396 ms/op
# Warmup Iteration   2: 8.995 ±(99.9%) 0.071 ms/op
# Warmup Iteration   3: 7.200 ±(99.9%) 0.027 ms/op
Iteration   1: 7.251 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.949 ms/op
                 listUser·p0.50:   6.857 ms/op
                 listUser·p0.90:   9.077 ms/op
                 listUser·p0.95:   10.322 ms/op
                 listUser·p0.99:   13.058 ms/op
                 listUser·p0.999:  29.356 ms/op
                 listUser·p0.9999: 31.843 ms/op
                 listUser·p1.00:   33.325 ms/op

Iteration   2: 6.760 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.163 ms/op
                 listUser·p0.50:   6.324 ms/op
                 listUser·p0.90:   8.233 ms/op
                 listUser·p0.95:   9.404 ms/op
                 listUser·p0.99:   13.544 ms/op
                 listUser·p0.999:  30.179 ms/op
                 listUser·p0.9999: 32.574 ms/op
                 listUser·p1.00:   32.899 ms/op

Iteration   3: 7.067 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   3.256 ms/op
                 listUser·p0.50:   6.480 ms/op
                 listUser·p0.90:   9.241 ms/op
                 listUser·p0.95:   10.895 ms/op
                 listUser·p0.99:   14.582 ms/op
                 listUser·p0.999:  29.080 ms/op
                 listUser·p0.9999: 32.371 ms/op
                 listUser·p1.00:   33.554 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 136651
  mean =      7.020 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 2363 
    [ 5.000,  7.500) = 101610 
    [ 7.500, 10.000) = 24947 
    [10.000, 12.500) = 5314 
    [12.500, 15.000) = 1449 
    [15.000, 17.500) = 486 
    [17.500, 20.000) = 137 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 111 
    [30.000, 32.500) = 101 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.163 ms/op
     p(50.0000) =      6.554 ms/op
     p(90.0000) =      8.847 ms/op
     p(95.0000) =     10.256 ms/op
     p(99.0000) =     13.926 ms/op
     p(99.9000) =     29.383 ms/op
     p(99.9900) =     32.113 ms/op
     p(99.9990) =     33.542 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


# Run complete. Total time: 00:13:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.463 ± 2.174  ops/ms
ClientPb.existUser                       thrpt       3   5.616 ± 3.911  ops/ms
ClientPb.getUser                         thrpt       3   5.067 ± 1.562  ops/ms
ClientPb.listUser                        thrpt       3   4.806 ± 1.337  ops/ms
ClientPb.createUser                       avgt       3   6.151 ± 3.430   ms/op
ClientPb.existUser                        avgt       3   5.671 ± 2.143   ms/op
ClientPb.getUser                          avgt       3   6.152 ± 4.026   ms/op
ClientPb.listUser                         avgt       3   7.109 ± 2.367   ms/op
ClientPb.createUser                     sample  158406   6.061 ± 0.015   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.958           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.652           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.561           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.733           ms/op
ClientPb.createUser:createUser·p0.99    sample          12.419           ms/op
ClientPb.createUser:createUser·p0.999   sample          31.392           ms/op
ClientPb.createUser:createUser·p0.9999  sample          37.487           ms/op
ClientPb.createUser:createUser·p1.00    sample          39.059           ms/op
ClientPb.existUser                      sample  168307   5.702 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.444           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.267           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.266           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.552           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.862           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.792           ms/op
ClientPb.existUser:existUser·p0.9999    sample          39.191           ms/op
ClientPb.existUser:existUser·p1.00      sample          47.120           ms/op
ClientPb.getUser                        sample  164537   5.834 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.305           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.464           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.283           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.552           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.993           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.430           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.275           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.979           ms/op
ClientPb.listUser                       sample  136651   7.020 ± 0.017   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.163           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.554           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.847           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.256           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.926           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.383           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.113           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.554           ms/op
