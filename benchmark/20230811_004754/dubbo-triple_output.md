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
# Warmup Iteration   1: 1.304 ops/ms
# Warmup Iteration   2: 2.906 ops/ms
# Warmup Iteration   3: 5.589 ops/ms
Iteration   1: 5.343 ops/ms
Iteration   2: 5.607 ops/ms
Iteration   3: 5.869 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.606 ±(99.9%) 4.804 ops/ms [Average]
  (min, avg, max) = (5.343, 5.606, 5.869), stdev = 0.263
  CI (99.9%): [0.803, 10.410] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.858 ops/ms
# Warmup Iteration   2: 4.944 ops/ms
# Warmup Iteration   3: 5.752 ops/ms
Iteration   1: 5.684 ops/ms
Iteration   2: 5.628 ops/ms
Iteration   3: 5.594 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.635 ±(99.9%) 0.825 ops/ms [Average]
  (min, avg, max) = (5.594, 5.635, 5.684), stdev = 0.045
  CI (99.9%): [4.810, 6.461] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.567 ops/ms
# Warmup Iteration   2: 4.824 ops/ms
# Warmup Iteration   3: 5.713 ops/ms
Iteration   1: 6.002 ops/ms
Iteration   2: 5.803 ops/ms
Iteration   3: 6.062 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.956 ±(99.9%) 2.472 ops/ms [Average]
  (min, avg, max) = (5.803, 5.956, 6.062), stdev = 0.135
  CI (99.9%): [3.484, 8.427] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.335 ops/ms
# Warmup Iteration   2: 4.211 ops/ms
# Warmup Iteration   3: 4.869 ops/ms
Iteration   1: 4.924 ops/ms
Iteration   2: 5.339 ops/ms
Iteration   3: 4.877 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.047 ±(99.9%) 4.636 ops/ms [Average]
  (min, avg, max) = (4.877, 5.047, 5.339), stdev = 0.254
  CI (99.9%): [0.411, 9.683] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 16.928 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 6.254 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.569 ±(99.9%) 0.009 ms/op
Iteration   1: 5.290 ±(99.9%) 0.012 ms/op
Iteration   2: 5.258 ±(99.9%) 0.009 ms/op
Iteration   3: 5.177 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.242 ±(99.9%) 1.064 ms/op [Average]
  (min, avg, max) = (5.177, 5.242, 5.290), stdev = 0.058
  CI (99.9%): [4.178, 6.306] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 19.562 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 6.704 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.796 ±(99.9%) 0.010 ms/op
Iteration   1: 5.344 ±(99.9%) 0.006 ms/op
Iteration   2: 5.181 ±(99.9%) 0.010 ms/op
Iteration   3: 5.151 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.225 ±(99.9%) 1.889 ms/op [Average]
  (min, avg, max) = (5.151, 5.225, 5.344), stdev = 0.104
  CI (99.9%): [3.337, 7.114] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 16.656 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 6.126 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.483 ±(99.9%) 0.012 ms/op
Iteration   1: 5.613 ±(99.9%) 0.009 ms/op
Iteration   2: 5.644 ±(99.9%) 0.008 ms/op
Iteration   3: 5.506 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.588 ±(99.9%) 1.326 ms/op [Average]
  (min, avg, max) = (5.506, 5.588, 5.644), stdev = 0.073
  CI (99.9%): [4.262, 6.914] (assumes normal distribution)


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
# Warmup Iteration   1: 18.962 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 7.410 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 6.309 ±(99.9%) 0.012 ms/op
Iteration   1: 6.365 ±(99.9%) 0.014 ms/op
Iteration   2: 6.125 ±(99.9%) 0.013 ms/op
Iteration   3: 6.300 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.263 ±(99.9%) 2.269 ms/op [Average]
  (min, avg, max) = (6.125, 6.263, 6.365), stdev = 0.124
  CI (99.9%): [3.994, 8.533] (assumes normal distribution)


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
# Warmup Iteration   1: 18.817 ±(99.9%) 0.273 ms/op
# Warmup Iteration   2: 7.438 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 6.379 ±(99.9%) 0.035 ms/op
Iteration   1: 5.893 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.249 ms/op
                 createUser·p0.50:   5.439 ms/op
                 createUser·p0.90:   7.717 ms/op
                 createUser·p0.95:   9.110 ms/op
                 createUser·p0.99:   13.080 ms/op
                 createUser·p0.999:  19.300 ms/op
                 createUser·p0.9999: 27.362 ms/op
                 createUser·p1.00:   28.049 ms/op

Iteration   2: 5.775 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.527 ms/op
                 createUser·p0.50:   5.366 ms/op
                 createUser·p0.90:   7.176 ms/op
                 createUser·p0.95:   8.438 ms/op
                 createUser·p0.99:   12.091 ms/op
                 createUser·p0.999:  27.874 ms/op
                 createUser·p0.9999: 34.039 ms/op
                 createUser·p1.00:   35.586 ms/op

Iteration   3: 6.119 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   2.486 ms/op
                 createUser·p0.50:   5.513 ms/op
                 createUser·p0.90:   8.487 ms/op
                 createUser·p0.95:   9.978 ms/op
                 createUser·p0.99:   12.993 ms/op
                 createUser·p0.999:  34.013 ms/op
                 createUser·p0.9999: 45.433 ms/op
                 createUser·p1.00:   49.873 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 161819
  mean =      5.926 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 44619 
    [ 5.000, 10.000) = 111369 
    [10.000, 15.000) = 5238 
    [15.000, 20.000) = 391 
    [20.000, 25.000) = 20 
    [25.000, 30.000) = 66 
    [30.000, 35.000) = 74 
    [35.000, 40.000) = 23 
    [40.000, 45.000) = 13 

  Percentiles, ms/op:
      p(0.0000) =      2.249 ms/op
     p(50.0000) =      5.431 ms/op
     p(90.0000) =      7.717 ms/op
     p(95.0000) =      9.257 ms/op
     p(99.0000) =     12.730 ms/op
     p(99.9000) =     27.465 ms/op
     p(99.9900) =     41.097 ms/op
     p(99.9990) =     49.670 ms/op
     p(99.9999) =     49.873 ms/op
    p(100.0000) =     49.873 ms/op


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
# Warmup Iteration   1: 18.307 ±(99.9%) 0.292 ms/op
# Warmup Iteration   2: 6.759 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.507 ±(99.9%) 0.024 ms/op
Iteration   1: 5.190 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.972 ms/op
                 existUser·p0.50:   4.964 ms/op
                 existUser·p0.90:   6.119 ms/op
                 existUser·p0.95:   7.274 ms/op
                 existUser·p0.99:   10.404 ms/op
                 existUser·p0.999:  23.478 ms/op
                 existUser·p0.9999: 32.184 ms/op
                 existUser·p1.00:   32.965 ms/op

Iteration   2: 5.581 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.380 ms/op
                 existUser·p0.50:   5.202 ms/op
                 existUser·p0.90:   7.094 ms/op
                 existUser·p0.95:   8.520 ms/op
                 existUser·p0.99:   11.239 ms/op
                 existUser·p0.999:  24.707 ms/op
                 existUser·p0.9999: 30.852 ms/op
                 existUser·p1.00:   31.850 ms/op

Iteration   3: 5.805 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   2.286 ms/op
                 existUser·p0.50:   5.399 ms/op
                 existUser·p0.90:   7.586 ms/op
                 existUser·p0.95:   8.602 ms/op
                 existUser·p0.99:   11.141 ms/op
                 existUser·p0.999:  30.179 ms/op
                 existUser·p0.9999: 42.664 ms/op
                 existUser·p1.00:   43.450 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 174145
  mean =      5.514 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 67772 
    [ 5.000, 10.000) = 103230 
    [10.000, 15.000) = 2854 
    [15.000, 20.000) = 94 
    [20.000, 25.000) = 56 
    [25.000, 30.000) = 49 
    [30.000, 35.000) = 58 
    [35.000, 40.000) = 9 
    [40.000, 45.000) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.972 ms/op
     p(50.0000) =      5.145 ms/op
     p(90.0000) =      6.996 ms/op
     p(95.0000) =      8.225 ms/op
     p(99.0000) =     10.961 ms/op
     p(99.9000) =     24.323 ms/op
     p(99.9900) =     40.894 ms/op
     p(99.9990) =     43.450 ms/op
     p(99.9999) =     43.450 ms/op
    p(100.0000) =     43.450 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 18.609 ±(99.9%) 0.322 ms/op
# Warmup Iteration   2: 6.629 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 5.559 ±(99.9%) 0.020 ms/op
Iteration   1: 5.472 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.874 ms/op
                 getUser·p0.50:   5.210 ms/op
                 getUser·p0.90:   6.595 ms/op
                 getUser·p0.95:   7.635 ms/op
                 getUser·p0.99:   10.186 ms/op
                 getUser·p0.999:  26.725 ms/op
                 getUser·p0.9999: 30.747 ms/op
                 getUser·p1.00:   33.522 ms/op

Iteration   2: 5.825 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   2.154 ms/op
                 getUser·p0.50:   5.399 ms/op
                 getUser·p0.90:   7.479 ms/op
                 getUser·p0.95:   8.700 ms/op
                 getUser·p0.99:   12.747 ms/op
                 getUser·p0.999:  25.908 ms/op
                 getUser·p0.9999: 29.803 ms/op
                 getUser·p1.00:   30.245 ms/op

Iteration   3: 5.953 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   2.314 ms/op
                 getUser·p0.50:   5.325 ms/op
                 getUser·p0.90:   8.405 ms/op
                 getUser·p0.95:   9.748 ms/op
                 getUser·p0.99:   12.682 ms/op
                 getUser·p0.999:  27.928 ms/op
                 getUser·p0.9999: 32.511 ms/op
                 getUser·p1.00:   34.537 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 167014
  mean =      5.743 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 56556 
    [ 5.000,  7.500) = 94534 
    [ 7.500, 10.000) = 11460 
    [10.000, 12.500) = 3029 
    [12.500, 15.000) = 857 
    [15.000, 17.500) = 240 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 101 
    [30.000, 32.500) = 46 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.874 ms/op
     p(50.0000) =      5.308 ms/op
     p(90.0000) =      7.365 ms/op
     p(95.0000) =      8.831 ms/op
     p(99.0000) =     12.091 ms/op
     p(99.9000) =     26.804 ms/op
     p(99.9900) =     32.057 ms/op
     p(99.9990) =     34.098 ms/op
     p(99.9999) =     34.537 ms/op
    p(100.0000) =     34.537 ms/op


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
# Warmup Iteration   1: 22.290 ±(99.9%) 0.386 ms/op
# Warmup Iteration   2: 8.581 ±(99.9%) 0.066 ms/op
# Warmup Iteration   3: 6.340 ±(99.9%) 0.026 ms/op
Iteration   1: 6.273 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.023 ms/op
                 listUser·p0.50:   5.825 ms/op
                 listUser·p0.90:   7.660 ms/op
                 listUser·p0.95:   9.257 ms/op
                 listUser·p0.99:   12.264 ms/op
                 listUser·p0.999:  24.312 ms/op
                 listUser·p0.9999: 28.334 ms/op
                 listUser·p1.00:   28.508 ms/op

Iteration   2: 6.607 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   3.342 ms/op
                 listUser·p0.50:   6.201 ms/op
                 listUser·p0.90:   8.020 ms/op
                 listUser·p0.95:   9.519 ms/op
                 listUser·p0.99:   13.389 ms/op
                 listUser·p0.999:  27.460 ms/op
                 listUser·p0.9999: 30.938 ms/op
                 listUser·p1.00:   33.554 ms/op

Iteration   3: 6.254 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.646 ms/op
                 listUser·p0.50:   5.956 ms/op
                 listUser·p0.90:   7.184 ms/op
                 listUser·p0.95:   8.151 ms/op
                 listUser·p0.99:   11.600 ms/op
                 listUser·p0.999:  24.145 ms/op
                 listUser·p0.9999: 33.171 ms/op
                 listUser·p1.00:   34.013 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 150565
  mean =      6.374 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 5387 
    [ 5.000,  7.500) = 128542 
    [ 7.500, 10.000) = 11683 
    [10.000, 12.500) = 3528 
    [12.500, 15.000) = 867 
    [15.000, 17.500) = 226 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 77 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.023 ms/op
     p(50.0000) =      5.964 ms/op
     p(90.0000) =      7.627 ms/op
     p(95.0000) =      8.978 ms/op
     p(99.0000) =     12.386 ms/op
     p(99.9000) =     25.569 ms/op
     p(99.9900) =     32.209 ms/op
     p(99.9990) =     33.947 ms/op
     p(99.9999) =     34.013 ms/op
    p(100.0000) =     34.013 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.606 ± 4.804  ops/ms
ClientPb.existUser                       thrpt       3   5.635 ± 0.825  ops/ms
ClientPb.getUser                         thrpt       3   5.956 ± 2.472  ops/ms
ClientPb.listUser                        thrpt       3   5.047 ± 4.636  ops/ms
ClientPb.createUser                       avgt       3   5.242 ± 1.064   ms/op
ClientPb.existUser                        avgt       3   5.225 ± 1.889   ms/op
ClientPb.getUser                          avgt       3   5.588 ± 1.326   ms/op
ClientPb.listUser                         avgt       3   6.263 ± 2.269   ms/op
ClientPb.createUser                     sample  161819   5.926 ± 0.015   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.249           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.431           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.717           ms/op
ClientPb.createUser:createUser·p0.95    sample           9.257           ms/op
ClientPb.createUser:createUser·p0.99    sample          12.730           ms/op
ClientPb.createUser:createUser·p0.999   sample          27.465           ms/op
ClientPb.createUser:createUser·p0.9999  sample          41.097           ms/op
ClientPb.createUser:createUser·p1.00    sample          49.873           ms/op
ClientPb.existUser                      sample  174145   5.514 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.972           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.145           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.996           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.225           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.961           ms/op
ClientPb.existUser:existUser·p0.999     sample          24.323           ms/op
ClientPb.existUser:existUser·p0.9999    sample          40.894           ms/op
ClientPb.existUser:existUser·p1.00      sample          43.450           ms/op
ClientPb.getUser                        sample  167014   5.743 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.874           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.308           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.365           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.831           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.091           ms/op
ClientPb.getUser:getUser·p0.999         sample          26.804           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.057           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.537           ms/op
ClientPb.listUser                       sample  150565   6.374 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.023           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.964           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.627           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.978           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.386           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.569           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.209           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.013           ms/op
