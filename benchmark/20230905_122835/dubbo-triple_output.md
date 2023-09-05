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
# Warmup Iteration   1: 1.057 ops/ms
# Warmup Iteration   2: 2.208 ops/ms
# Warmup Iteration   3: 5.041 ops/ms
Iteration   1: 5.185 ops/ms
Iteration   2: 5.708 ops/ms
Iteration   3: 5.789 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.561 ±(99.9%) 5.975 ops/ms [Average]
  (min, avg, max) = (5.185, 5.561, 5.789), stdev = 0.328
  CI (99.9%): [≈ 0, 11.536] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.550 ops/ms
# Warmup Iteration   2: 4.229 ops/ms
# Warmup Iteration   3: 5.688 ops/ms
Iteration   1: 5.950 ops/ms
Iteration   2: 6.049 ops/ms
Iteration   3: 5.856 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.952 ±(99.9%) 1.759 ops/ms [Average]
  (min, avg, max) = (5.856, 5.952, 6.049), stdev = 0.096
  CI (99.9%): [4.193, 7.711] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.395 ops/ms
# Warmup Iteration   2: 3.521 ops/ms
# Warmup Iteration   3: 5.400 ops/ms
Iteration   1: 5.560 ops/ms
Iteration   2: 5.523 ops/ms
Iteration   3: 5.826 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.636 ±(99.9%) 3.022 ops/ms [Average]
  (min, avg, max) = (5.523, 5.636, 5.826), stdev = 0.166
  CI (99.9%): [2.614, 8.658] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 1.466 ops/ms
# Warmup Iteration   2: 3.792 ops/ms
# Warmup Iteration   3: 4.546 ops/ms
Iteration   1: 4.829 ops/ms
Iteration   2: 4.789 ops/ms
Iteration   3: 4.781 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.800 ±(99.9%) 0.468 ops/ms [Average]
  (min, avg, max) = (4.781, 4.800, 4.829), stdev = 0.026
  CI (99.9%): [4.332, 5.268] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 21.846 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 8.345 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.493 ±(99.9%) 0.012 ms/op
Iteration   1: 6.312 ±(99.9%) 0.010 ms/op
Iteration   2: 5.839 ±(99.9%) 0.013 ms/op
Iteration   3: 5.741 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.964 ±(99.9%) 5.565 ms/op [Average]
  (min, avg, max) = (5.741, 5.964, 6.312), stdev = 0.305
  CI (99.9%): [0.399, 11.529] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 17.221 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 6.520 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.608 ±(99.9%) 0.008 ms/op
Iteration   1: 5.551 ±(99.9%) 0.007 ms/op
Iteration   2: 5.528 ±(99.9%) 0.014 ms/op
Iteration   3: 5.456 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.512 ±(99.9%) 0.897 ms/op [Average]
  (min, avg, max) = (5.456, 5.512, 5.551), stdev = 0.049
  CI (99.9%): [4.614, 6.409] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 19.554 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 7.297 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 5.925 ±(99.9%) 0.006 ms/op
Iteration   1: 5.654 ±(99.9%) 0.015 ms/op
Iteration   2: 5.603 ±(99.9%) 0.012 ms/op
Iteration   3: 5.843 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.700 ±(99.9%) 2.309 ms/op [Average]
  (min, avg, max) = (5.603, 5.700, 5.843), stdev = 0.127
  CI (99.9%): [3.391, 8.009] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 18.720 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 8.084 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 6.832 ±(99.9%) 0.011 ms/op
Iteration   1: 6.609 ±(99.9%) 0.014 ms/op
Iteration   2: 6.546 ±(99.9%) 0.011 ms/op
Iteration   3: 6.696 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.617 ±(99.9%) 1.378 ms/op [Average]
  (min, avg, max) = (6.546, 6.617, 6.696), stdev = 0.076
  CI (99.9%): [5.239, 7.995] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 19.141 ±(99.9%) 0.338 ms/op
# Warmup Iteration   2: 7.680 ±(99.9%) 0.059 ms/op
# Warmup Iteration   3: 6.234 ±(99.9%) 0.031 ms/op
Iteration   1: 5.967 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.531 ms/op
                 createUser·p0.50:   5.579 ms/op
                 createUser·p0.90:   7.397 ms/op
                 createUser·p0.95:   8.667 ms/op
                 createUser·p0.99:   11.551 ms/op
                 createUser·p0.999:  27.586 ms/op
                 createUser·p0.9999: 35.646 ms/op
                 createUser·p1.00:   36.372 ms/op

Iteration   2: 6.049 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.540 ms/op
                 createUser·p0.50:   5.620 ms/op
                 createUser·p0.90:   7.561 ms/op
                 createUser·p0.95:   9.134 ms/op
                 createUser·p0.99:   12.817 ms/op
                 createUser·p0.999:  19.360 ms/op
                 createUser·p0.9999: 31.447 ms/op
                 createUser·p1.00:   32.408 ms/op

Iteration   3: 6.072 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   2.021 ms/op
                 createUser·p0.50:   5.751 ms/op
                 createUser·p0.90:   7.438 ms/op
                 createUser·p0.95:   8.552 ms/op
                 createUser·p0.99:   12.255 ms/op
                 createUser·p0.999:  31.270 ms/op
                 createUser·p0.9999: 42.187 ms/op
                 createUser·p1.00:   44.106 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 159217
  mean =      6.029 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 28094 
    [ 5.000, 10.000) = 127035 
    [10.000, 15.000) = 3578 
    [15.000, 20.000) = 266 
    [20.000, 25.000) = 77 
    [25.000, 30.000) = 61 
    [30.000, 35.000) = 64 
    [35.000, 40.000) = 22 
    [40.000, 45.000) = 20 

  Percentiles, ms/op:
      p(0.0000) =      2.021 ms/op
     p(50.0000) =      5.652 ms/op
     p(90.0000) =      7.463 ms/op
     p(95.0000) =      8.798 ms/op
     p(99.0000) =     12.288 ms/op
     p(99.9000) =     25.552 ms/op
     p(99.9900) =     40.436 ms/op
     p(99.9990) =     43.097 ms/op
     p(99.9999) =     44.106 ms/op
    p(100.0000) =     44.106 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 19.222 ±(99.9%) 0.336 ms/op
# Warmup Iteration   2: 7.000 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 6.009 ±(99.9%) 0.024 ms/op
Iteration   1: 5.721 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.556 ms/op
                 existUser·p0.50:   5.284 ms/op
                 existUser·p0.90:   7.160 ms/op
                 existUser·p0.95:   8.570 ms/op
                 existUser·p0.99:   11.452 ms/op
                 existUser·p0.999:  21.823 ms/op
                 existUser·p0.9999: 28.712 ms/op
                 existUser·p1.00:   29.491 ms/op

Iteration   2: 5.453 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.662 ms/op
                 existUser·p0.50:   5.169 ms/op
                 existUser·p0.90:   6.611 ms/op
                 existUser·p0.95:   7.487 ms/op
                 existUser·p0.99:   10.551 ms/op
                 existUser·p0.999:  27.623 ms/op
                 existUser·p0.9999: 31.818 ms/op
                 existUser·p1.00:   32.637 ms/op

Iteration   3: 5.541 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.311 ms/op
                 existUser·p0.50:   5.243 ms/op
                 existUser·p0.90:   6.627 ms/op
                 existUser·p0.95:   7.750 ms/op
                 existUser·p0.99:   10.812 ms/op
                 existUser·p0.999:  30.367 ms/op
                 existUser·p0.9999: 38.187 ms/op
                 existUser·p1.00:   39.780 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 172298
  mean =      5.570 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 58000 
    [ 5.000,  7.500) = 103687 
    [ 7.500, 10.000) = 7667 
    [10.000, 12.500) = 1924 
    [12.500, 15.000) = 486 
    [15.000, 17.500) = 188 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 43 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 55 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.311 ms/op
     p(50.0000) =      5.226 ms/op
     p(90.0000) =      6.808 ms/op
     p(95.0000) =      7.905 ms/op
     p(99.0000) =     11.043 ms/op
     p(99.9000) =     26.411 ms/op
     p(99.9900) =     36.357 ms/op
     p(99.9990) =     39.212 ms/op
     p(99.9999) =     39.780 ms/op
    p(100.0000) =     39.780 ms/op


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
# Warmup Iteration   1: 18.661 ±(99.9%) 0.297 ms/op
# Warmup Iteration   2: 6.946 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 6.654 ±(99.9%) 0.035 ms/op
Iteration   1: 8.290 ±(99.9%) 0.054 ms/op
                 getUser·p0.00:   3.052 ms/op
                 getUser·p0.50:   7.299 ms/op
                 getUser·p0.90:   12.534 ms/op
                 getUser·p0.95:   14.828 ms/op
                 getUser·p0.99:   19.520 ms/op
                 getUser·p0.999:  31.440 ms/op
                 getUser·p0.9999: 36.390 ms/op
                 getUser·p1.00:   37.290 ms/op

Iteration   2: 7.723 ±(99.9%) 0.049 ms/op
                 getUser·p0.00:   0.578 ms/op
                 getUser·p0.50:   6.849 ms/op
                 getUser·p0.90:   11.321 ms/op
                 getUser·p0.95:   13.359 ms/op
                 getUser·p0.99:   18.837 ms/op
                 getUser·p0.999:  28.508 ms/op
                 getUser·p0.9999: 44.555 ms/op
                 getUser·p1.00:   44.761 ms/op

Iteration   3: 7.853 ±(99.9%) 0.047 ms/op
                 getUser·p0.00:   2.613 ms/op
                 getUser·p0.50:   7.094 ms/op
                 getUser·p0.90:   11.420 ms/op
                 getUser·p0.95:   13.271 ms/op
                 getUser·p0.99:   17.629 ms/op
                 getUser·p0.999:  22.184 ms/op
                 getUser·p0.9999: 43.511 ms/op
                 getUser·p1.00:   43.647 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 120750
  mean =      7.949 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 6579 
    [ 5.000, 10.000) = 92278 
    [10.000, 15.000) = 17803 
    [15.000, 20.000) = 3300 
    [20.000, 25.000) = 567 
    [25.000, 30.000) = 114 
    [30.000, 35.000) = 28 
    [35.000, 40.000) = 32 
    [40.000, 45.000) = 49 

  Percentiles, ms/op:
      p(0.0000) =      0.578 ms/op
     p(50.0000) =      7.070 ms/op
     p(90.0000) =     11.731 ms/op
     p(95.0000) =     13.828 ms/op
     p(99.0000) =     18.678 ms/op
     p(99.9000) =     28.549 ms/op
     p(99.9900) =     43.839 ms/op
     p(99.9990) =     44.747 ms/op
     p(99.9999) =     44.761 ms/op
    p(100.0000) =     44.761 ms/op


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
# Warmup Iteration   1: 26.248 ±(99.9%) 0.543 ms/op
# Warmup Iteration   2: 9.750 ±(99.9%) 0.093 ms/op
# Warmup Iteration   3: 7.594 ±(99.9%) 0.046 ms/op
Iteration   1: 7.112 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.351 ms/op
                 listUser·p0.50:   6.750 ms/op
                 listUser·p0.90:   8.536 ms/op
                 listUser·p0.95:   10.027 ms/op
                 listUser·p0.99:   13.697 ms/op
                 listUser·p0.999:  28.443 ms/op
                 listUser·p0.9999: 31.801 ms/op
                 listUser·p1.00:   33.423 ms/op

Iteration   2: 6.887 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.576 ms/op
                 listUser·p0.50:   6.545 ms/op
                 listUser·p0.90:   8.225 ms/op
                 listUser·p0.95:   9.339 ms/op
                 listUser·p0.99:   12.976 ms/op
                 listUser·p0.999:  31.836 ms/op
                 listUser·p0.9999: 36.817 ms/op
                 listUser·p1.00:   38.207 ms/op

Iteration   3: 6.949 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   3.248 ms/op
                 listUser·p0.50:   6.423 ms/op
                 listUser·p0.90:   8.651 ms/op
                 listUser·p0.95:   9.814 ms/op
                 listUser·p0.99:   14.024 ms/op
                 listUser·p0.999:  31.719 ms/op
                 listUser·p0.9999: 33.908 ms/op
                 listUser·p1.00:   34.865 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 137416
  mean =      6.982 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 1913 
    [ 5.000,  7.500) = 106743 
    [ 7.500, 10.000) = 22568 
    [10.000, 12.500) = 4105 
    [12.500, 15.000) = 1224 
    [15.000, 17.500) = 397 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 84 
    [30.000, 32.500) = 99 
    [32.500, 35.000) = 61 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      2.351 ms/op
     p(50.0000) =      6.578 ms/op
     p(90.0000) =      8.471 ms/op
     p(95.0000) =      9.732 ms/op
     p(99.0000) =     13.533 ms/op
     p(99.9000) =     30.695 ms/op
     p(99.9900) =     35.001 ms/op
     p(99.9990) =     38.036 ms/op
     p(99.9999) =     38.207 ms/op
    p(100.0000) =     38.207 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.561 ± 5.975  ops/ms
ClientPb.existUser                       thrpt       3   5.952 ± 1.759  ops/ms
ClientPb.getUser                         thrpt       3   5.636 ± 3.022  ops/ms
ClientPb.listUser                        thrpt       3   4.800 ± 0.468  ops/ms
ClientPb.createUser                       avgt       3   5.964 ± 5.565   ms/op
ClientPb.existUser                        avgt       3   5.512 ± 0.897   ms/op
ClientPb.getUser                          avgt       3   5.700 ± 2.309   ms/op
ClientPb.listUser                         avgt       3   6.617 ± 1.378   ms/op
ClientPb.createUser                     sample  159217   6.029 ± 0.014   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.021           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.652           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.463           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.798           ms/op
ClientPb.createUser:createUser·p0.99    sample          12.288           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.552           ms/op
ClientPb.createUser:createUser·p0.9999  sample          40.436           ms/op
ClientPb.createUser:createUser·p1.00    sample          44.106           ms/op
ClientPb.existUser                      sample  172298   5.570 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.311           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.226           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.808           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.905           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.043           ms/op
ClientPb.existUser:existUser·p0.999     sample          26.411           ms/op
ClientPb.existUser:existUser·p0.9999    sample          36.357           ms/op
ClientPb.existUser:existUser·p1.00      sample          39.780           ms/op
ClientPb.getUser                        sample  120750   7.949 ± 0.029   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.578           ms/op
ClientPb.getUser:getUser·p0.50          sample           7.070           ms/op
ClientPb.getUser:getUser·p0.90          sample          11.731           ms/op
ClientPb.getUser:getUser·p0.95          sample          13.828           ms/op
ClientPb.getUser:getUser·p0.99          sample          18.678           ms/op
ClientPb.getUser:getUser·p0.999         sample          28.549           ms/op
ClientPb.getUser:getUser·p0.9999        sample          43.839           ms/op
ClientPb.getUser:getUser·p1.00          sample          44.761           ms/op
ClientPb.listUser                       sample  137416   6.982 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.351           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.578           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.471           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.732           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.533           ms/op
ClientPb.listUser:listUser·p0.999       sample          30.695           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.001           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.207           ms/op
