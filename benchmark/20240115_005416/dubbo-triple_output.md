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
# Warmup Iteration   1: 5.390 ops/ms
# Warmup Iteration   2: 12.044 ops/ms
# Warmup Iteration   3: 12.452 ops/ms
Iteration   1: 12.473 ops/ms
Iteration   2: 12.834 ops/ms
Iteration   3: 12.856 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.721 ±(99.9%) 3.924 ops/ms [Average]
  (min, avg, max) = (12.473, 12.721, 12.856), stdev = 0.215
  CI (99.9%): [8.796, 16.645] (assumes normal distribution)


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
# Warmup Iteration   1: 8.543 ops/ms
# Warmup Iteration   2: 13.264 ops/ms
# Warmup Iteration   3: 13.340 ops/ms
Iteration   1: 13.298 ops/ms
Iteration   2: 13.335 ops/ms
Iteration   3: 13.369 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.334 ±(99.9%) 0.652 ops/ms [Average]
  (min, avg, max) = (13.298, 13.334, 13.369), stdev = 0.036
  CI (99.9%): [12.682, 13.986] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.168 ops/ms
# Warmup Iteration   2: 12.656 ops/ms
# Warmup Iteration   3: 12.852 ops/ms
Iteration   1: 13.041 ops/ms
Iteration   2: 13.027 ops/ms
Iteration   3: 13.143 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.070 ±(99.9%) 1.153 ops/ms [Average]
  (min, avg, max) = (13.027, 13.070, 13.143), stdev = 0.063
  CI (99.9%): [11.917, 14.223] (assumes normal distribution)


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
# Warmup Iteration   1: 7.130 ops/ms
# Warmup Iteration   2: 10.737 ops/ms
# Warmup Iteration   3: 10.863 ops/ms
Iteration   1: 10.977 ops/ms
Iteration   2: 10.936 ops/ms
Iteration   3: 10.945 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.953 ±(99.9%) 0.397 ops/ms [Average]
  (min, avg, max) = (10.936, 10.953, 10.977), stdev = 0.022
  CI (99.9%): [10.556, 11.350] (assumes normal distribution)


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
# Warmup Iteration   1: 4.004 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.585 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.446 ±(99.9%) 0.004 ms/op
Iteration   1: 2.514 ±(99.9%) 0.004 ms/op
Iteration   2: 2.471 ±(99.9%) 0.003 ms/op
Iteration   3: 2.460 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.481 ±(99.9%) 0.520 ms/op [Average]
  (min, avg, max) = (2.460, 2.481, 2.514), stdev = 0.029
  CI (99.9%): [1.961, 3.002] (assumes normal distribution)


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
# Warmup Iteration   1: 3.606 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.432 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.433 ±(99.9%) 0.004 ms/op
Iteration   1: 2.416 ±(99.9%) 0.003 ms/op
Iteration   2: 2.418 ±(99.9%) 0.003 ms/op
Iteration   3: 2.428 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.421 ±(99.9%) 0.114 ms/op [Average]
  (min, avg, max) = (2.416, 2.421, 2.428), stdev = 0.006
  CI (99.9%): [2.307, 2.534] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.814 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.551 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.476 ±(99.9%) 0.003 ms/op
Iteration   1: 2.443 ±(99.9%) 0.003 ms/op
Iteration   2: 2.482 ±(99.9%) 0.004 ms/op
Iteration   3: 2.466 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.464 ±(99.9%) 0.357 ms/op [Average]
  (min, avg, max) = (2.443, 2.464, 2.482), stdev = 0.020
  CI (99.9%): [2.107, 2.821] (assumes normal distribution)


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
# Warmup Iteration   1: 4.628 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.056 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.004 ms/op
Iteration   1: 2.980 ±(99.9%) 0.005 ms/op
Iteration   2: 2.989 ±(99.9%) 0.005 ms/op
Iteration   3: 2.991 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.987 ±(99.9%) 0.106 ms/op [Average]
  (min, avg, max) = (2.980, 2.987, 2.991), stdev = 0.006
  CI (99.9%): [2.881, 3.093] (assumes normal distribution)


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
# Warmup Iteration   1: 3.979 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.630 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.470 ±(99.9%) 0.005 ms/op
Iteration   1: 2.471 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.830 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.092 ms/op
                 createUser·p0.99:   3.686 ms/op
                 createUser·p0.999:  6.903 ms/op
                 createUser·p0.9999: 14.159 ms/op
                 createUser·p1.00:   14.975 ms/op

Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.880 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   3.621 ms/op
                 createUser·p0.999:  6.889 ms/op
                 createUser·p0.9999: 11.863 ms/op
                 createUser·p1.00:   12.239 ms/op

Iteration   3: 2.498 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.992 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   4.059 ms/op
                 createUser·p0.999:  8.684 ms/op
                 createUser·p0.9999: 9.870 ms/op
                 createUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 387084
  mean =      2.477 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 188123 
    [ 2.500,  3.750) = 194789 
    [ 3.750,  5.000) = 3266 
    [ 5.000,  6.250) = 400 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 148 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.830 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.785 ms/op
     p(99.9000) =      8.666 ms/op
     p(99.9900) =     13.435 ms/op
     p(99.9990) =     14.447 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


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
# Warmup Iteration   1: 3.639 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.447 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.407 ±(99.9%) 0.005 ms/op
Iteration   1: 2.419 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.010 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.387 ms/op
                 existUser·p0.999:  5.793 ms/op
                 existUser·p0.9999: 14.627 ms/op
                 existUser·p1.00:   14.975 ms/op

Iteration   2: 2.432 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.693 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.506 ms/op
                 existUser·p0.999:  5.792 ms/op
                 existUser·p0.9999: 12.901 ms/op
                 existUser·p1.00:   13.730 ms/op

Iteration   3: 2.419 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.871 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.682 ms/op
                 existUser·p0.999:  7.840 ms/op
                 existUser·p0.9999: 12.698 ms/op
                 existUser·p1.00:   13.124 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395734
  mean =      2.423 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 197039 
    [ 2.500,  3.750) = 195890 
    [ 3.750,  5.000) = 2137 
    [ 5.000,  6.250) = 226 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 124 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.945 ms/op
     p(95.0000) =      3.047 ms/op
     p(99.0000) =      3.527 ms/op
     p(99.9000) =      6.136 ms/op
     p(99.9900) =     13.341 ms/op
     p(99.9990) =     14.811 ms/op
     p(99.9999) =     14.975 ms/op
    p(100.0000) =     14.975 ms/op


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
# Warmup Iteration   1: 4.048 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.550 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.006 ms/op
Iteration   1: 2.463 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.006 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.707 ms/op
                 getUser·p0.999:  6.270 ms/op
                 getUser·p0.9999: 13.484 ms/op
                 getUser·p1.00:   13.943 ms/op

Iteration   2: 2.512 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.932 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.252 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  10.011 ms/op
                 getUser·p0.9999: 12.126 ms/op
                 getUser·p1.00:   13.074 ms/op

Iteration   3: 2.472 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.019 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.883 ms/op
                 getUser·p0.999:  6.950 ms/op
                 getUser·p0.9999: 10.470 ms/op
                 getUser·p1.00:   11.174 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386386
  mean =      2.482 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 91 
    [ 1.250,  2.500) = 193765 
    [ 2.500,  3.750) = 186381 
    [ 3.750,  5.000) = 4795 
    [ 5.000,  6.250) = 854 
    [ 6.250,  7.500) = 57 
    [ 7.500,  8.750) = 69 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 111 
    [11.250, 12.500) = 111 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.932 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      4.088 ms/op
     p(99.9000) =      8.128 ms/op
     p(99.9900) =     12.998 ms/op
     p(99.9990) =     13.683 ms/op
     p(99.9999) =     13.943 ms/op
    p(100.0000) =     13.943 ms/op


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
# Warmup Iteration   1: 4.443 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 2.980 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.948 ±(99.9%) 0.008 ms/op
Iteration   1: 2.948 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.849 ms/op
                 listUser·p0.50:   2.888 ms/op
                 listUser·p0.90:   3.793 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  9.208 ms/op
                 listUser·p0.9999: 11.373 ms/op
                 listUser·p1.00:   12.370 ms/op

Iteration   2: 2.944 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.010 ms/op
                 listUser·p0.50:   2.879 ms/op
                 listUser·p0.90:   3.805 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.404 ms/op
                 listUser·p0.9999: 11.488 ms/op
                 listUser·p1.00:   12.501 ms/op

Iteration   3: 2.938 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.861 ms/op
                 listUser·p0.50:   2.879 ms/op
                 listUser·p0.90:   3.785 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  8.769 ms/op
                 listUser·p0.9999: 10.752 ms/op
                 listUser·p1.00:   11.174 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 325819
  mean =      2.944 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 177 
    [ 1.250,  2.500) = 105501 
    [ 2.500,  3.750) = 185316 
    [ 3.750,  5.000) = 28147 
    [ 5.000,  6.250) = 5514 
    [ 6.250,  7.500) = 484 
    [ 7.500,  8.750) = 232 
    [ 8.750, 10.000) = 309 
    [10.000, 11.250) = 109 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.849 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =      9.110 ms/op
     p(99.9900) =     11.155 ms/op
     p(99.9990) =     12.349 ms/op
     p(99.9999) =     12.501 ms/op
    p(100.0000) =     12.501 ms/op


# Run complete. Total time: 00:12:56

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.721 ± 3.924  ops/ms
ClientPb.existUser                       thrpt       3  13.334 ± 0.652  ops/ms
ClientPb.getUser                         thrpt       3  13.070 ± 1.153  ops/ms
ClientPb.listUser                        thrpt       3  10.953 ± 0.397  ops/ms
ClientPb.createUser                       avgt       3   2.481 ± 0.520   ms/op
ClientPb.existUser                        avgt       3   2.421 ± 0.114   ms/op
ClientPb.getUser                          avgt       3   2.464 ± 0.357   ms/op
ClientPb.listUser                         avgt       3   2.987 ± 0.106   ms/op
ClientPb.createUser                     sample  387084   2.477 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.830           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.552           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.006           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.129           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.785           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.666           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.435           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.924           ms/op
ClientPb.existUser                      sample  395734   2.423 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.693           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.945           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.527           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.136           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.341           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.975           ms/op
ClientPb.getUser                        sample  386386   2.482 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.932           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.494           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.027           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.088           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.128           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.998           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.943           ms/op
ClientPb.listUser                       sample  325819   2.944 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.849           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.884           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.793           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.497           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.110           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.155           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.501           ms/op
