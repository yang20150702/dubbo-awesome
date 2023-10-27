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
# Warmup Iteration   1: 1.665 ops/ms
# Warmup Iteration   2: 3.384 ops/ms
# Warmup Iteration   3: 6.656 ops/ms
Iteration   1: 7.507 ops/ms
Iteration   2: 7.724 ops/ms
Iteration   3: 7.897 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.709 ±(99.9%) 3.566 ops/ms [Average]
  (min, avg, max) = (7.507, 7.709, 7.897), stdev = 0.195
  CI (99.9%): [4.143, 11.276] (assumes normal distribution)


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
# Warmup Iteration   1: 2.079 ops/ms
# Warmup Iteration   2: 6.304 ops/ms
# Warmup Iteration   3: 7.960 ops/ms
Iteration   1: 8.265 ops/ms
Iteration   2: 8.551 ops/ms
Iteration   3: 8.394 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.403 ±(99.9%) 2.615 ops/ms [Average]
  (min, avg, max) = (8.265, 8.403, 8.551), stdev = 0.143
  CI (99.9%): [5.789, 11.018] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.235 ops/ms
# Warmup Iteration   2: 6.762 ops/ms
# Warmup Iteration   3: 7.986 ops/ms
Iteration   1: 7.794 ops/ms
Iteration   2: 8.043 ops/ms
Iteration   3: 7.661 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.833 ±(99.9%) 3.536 ops/ms [Average]
  (min, avg, max) = (7.661, 7.833, 8.043), stdev = 0.194
  CI (99.9%): [4.297, 11.369] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.245 ops/ms
# Warmup Iteration   2: 5.709 ops/ms
# Warmup Iteration   3: 6.680 ops/ms
Iteration   1: 6.771 ops/ms
Iteration   2: 6.609 ops/ms
Iteration   3: 6.758 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.713 ±(99.9%) 1.646 ops/ms [Average]
  (min, avg, max) = (6.609, 6.713, 6.771), stdev = 0.090
  CI (99.9%): [5.067, 8.358] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 13.494 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 4.884 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.179 ±(99.9%) 0.007 ms/op
Iteration   1: 4.050 ±(99.9%) 0.005 ms/op
Iteration   2: 4.096 ±(99.9%) 0.006 ms/op
Iteration   3: 4.097 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.081 ±(99.9%) 0.489 ms/op [Average]
  (min, avg, max) = (4.050, 4.081, 4.097), stdev = 0.027
  CI (99.9%): [3.592, 4.570] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 13.316 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.534 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.866 ±(99.9%) 0.006 ms/op
Iteration   1: 3.896 ±(99.9%) 0.006 ms/op
Iteration   2: 3.914 ±(99.9%) 0.003 ms/op
Iteration   3: 3.828 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.879 ±(99.9%) 0.821 ms/op [Average]
  (min, avg, max) = (3.828, 3.879, 3.914), stdev = 0.045
  CI (99.9%): [3.058, 4.701] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 13.964 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.635 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.154 ±(99.9%) 0.003 ms/op
Iteration   1: 4.039 ±(99.9%) 0.005 ms/op
Iteration   2: 3.986 ±(99.9%) 0.008 ms/op
Iteration   3: 3.961 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.995 ±(99.9%) 0.730 ms/op [Average]
  (min, avg, max) = (3.961, 3.995, 4.039), stdev = 0.040
  CI (99.9%): [3.265, 4.725] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 15.520 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 5.739 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.872 ±(99.9%) 0.008 ms/op
Iteration   1: 4.966 ±(99.9%) 0.008 ms/op
Iteration   2: 4.794 ±(99.9%) 0.007 ms/op
Iteration   3: 4.777 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.846 ±(99.9%) 1.906 ms/op [Average]
  (min, avg, max) = (4.777, 4.846, 4.966), stdev = 0.104
  CI (99.9%): [2.940, 6.751] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 12.844 ±(99.9%) 0.204 ms/op
# Warmup Iteration   2: 5.658 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 4.463 ±(99.9%) 0.019 ms/op
Iteration   1: 4.397 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.823 ms/op
                 createUser·p0.50:   4.006 ms/op
                 createUser·p0.90:   5.497 ms/op
                 createUser·p0.95:   7.037 ms/op
                 createUser·p0.99:   10.158 ms/op
                 createUser·p0.999:  20.480 ms/op
                 createUser·p0.9999: 25.723 ms/op
                 createUser·p1.00:   26.214 ms/op

Iteration   2: 4.202 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.522 ms/op
                 createUser·p0.50:   4.022 ms/op
                 createUser·p0.90:   4.940 ms/op
                 createUser·p0.95:   5.358 ms/op
                 createUser·p0.99:   7.414 ms/op
                 createUser·p0.999:  13.448 ms/op
                 createUser·p0.9999: 24.470 ms/op
                 createUser·p1.00:   25.133 ms/op

Iteration   3: 4.153 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.948 ms/op
                 createUser·p0.50:   3.998 ms/op
                 createUser·p0.90:   4.760 ms/op
                 createUser·p0.95:   5.046 ms/op
                 createUser·p0.99:   7.373 ms/op
                 createUser·p0.999:  27.361 ms/op
                 createUser·p0.9999: 31.595 ms/op
                 createUser·p1.00:   33.128 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 225901
  mean =      4.248 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 259 
    [ 2.500,  5.000) = 205051 
    [ 5.000,  7.500) = 16408 
    [ 7.500, 10.000) = 2840 
    [10.000, 12.500) = 811 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.522 ms/op
     p(50.0000) =      4.010 ms/op
     p(90.0000) =      4.948 ms/op
     p(95.0000) =      5.661 ms/op
     p(99.0000) =      9.028 ms/op
     p(99.9000) =     21.764 ms/op
     p(99.9900) =     30.783 ms/op
     p(99.9990) =     32.877 ms/op
     p(99.9999) =     33.128 ms/op
    p(100.0000) =     33.128 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.285 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 4.635 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.057 ±(99.9%) 0.012 ms/op
Iteration   1: 3.892 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.718 ms/op
                 existUser·p0.50:   3.736 ms/op
                 existUser·p0.90:   4.366 ms/op
                 existUser·p0.95:   4.702 ms/op
                 existUser·p0.99:   6.990 ms/op
                 existUser·p0.999:  18.771 ms/op
                 existUser·p0.9999: 22.210 ms/op
                 existUser·p1.00:   22.610 ms/op

Iteration   2: 3.968 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.366 ms/op
                 existUser·p0.50:   3.809 ms/op
                 existUser·p0.90:   4.334 ms/op
                 existUser·p0.95:   5.046 ms/op
                 existUser·p0.99:   8.036 ms/op
                 existUser·p0.999:  12.475 ms/op
                 existUser·p0.9999: 22.475 ms/op
                 existUser·p1.00:   22.938 ms/op

Iteration   3: 3.911 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.153 ms/op
                 existUser·p0.50:   3.768 ms/op
                 existUser·p0.90:   4.276 ms/op
                 existUser·p0.95:   4.547 ms/op
                 existUser·p0.99:   7.741 ms/op
                 existUser·p0.999:  13.763 ms/op
                 existUser·p0.9999: 25.763 ms/op
                 existUser·p1.00:   26.837 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 244703
  mean =      3.924 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 212 
    [ 2.500,  5.000) = 235150 
    [ 5.000,  7.500) = 6400 
    [ 7.500, 10.000) = 2251 
    [10.000, 12.500) = 349 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.153 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      7.774 ms/op
     p(99.9000) =     16.908 ms/op
     p(99.9900) =     24.838 ms/op
     p(99.9990) =     26.545 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.462 ±(99.9%) 0.195 ms/op
# Warmup Iteration   2: 4.767 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.230 ±(99.9%) 0.015 ms/op
Iteration   1: 4.105 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.097 ms/op
                 getUser·p0.50:   3.903 ms/op
                 getUser·p0.90:   4.555 ms/op
                 getUser·p0.95:   5.202 ms/op
                 getUser·p0.99:   8.487 ms/op
                 getUser·p0.999:  23.040 ms/op
                 getUser·p0.9999: 25.861 ms/op
                 getUser·p1.00:   27.558 ms/op

Iteration   2: 4.057 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.767 ms/op
                 getUser·p0.50:   3.936 ms/op
                 getUser·p0.90:   4.481 ms/op
                 getUser·p0.95:   4.743 ms/op
                 getUser·p0.99:   6.717 ms/op
                 getUser·p0.999:  14.352 ms/op
                 getUser·p0.9999: 26.513 ms/op
                 getUser·p1.00:   27.394 ms/op

Iteration   3: 4.039 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.954 ms/op
                 getUser·p0.50:   3.928 ms/op
                 getUser·p0.90:   4.456 ms/op
                 getUser·p0.95:   4.743 ms/op
                 getUser·p0.99:   6.775 ms/op
                 getUser·p0.999:  26.861 ms/op
                 getUser·p0.9999: 28.878 ms/op
                 getUser·p1.00:   29.852 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 236010
  mean =      4.067 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 76 
    [ 2.500,  5.000) = 226126 
    [ 5.000,  7.500) = 7569 
    [ 7.500, 10.000) = 1532 
    [10.000, 12.500) = 250 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 108 

  Percentiles, ms/op:
      p(0.0000) =      1.767 ms/op
     p(50.0000) =      3.924 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      7.406 ms/op
     p(99.9000) =     23.133 ms/op
     p(99.9900) =     28.213 ms/op
     p(99.9990) =     29.420 ms/op
     p(99.9999) =     29.852 ms/op
    p(100.0000) =     29.852 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 17.207 ±(99.9%) 0.235 ms/op
# Warmup Iteration   2: 6.051 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.018 ±(99.9%) 0.016 ms/op
Iteration   1: 4.893 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.434 ms/op
                 listUser·p0.50:   4.710 ms/op
                 listUser·p0.90:   5.333 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   8.569 ms/op
                 listUser·p0.999:  24.238 ms/op
                 listUser·p0.9999: 26.047 ms/op
                 listUser·p1.00:   27.263 ms/op

Iteration   2: 4.909 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.355 ms/op
                 listUser·p0.50:   4.686 ms/op
                 listUser·p0.90:   5.480 ms/op
                 listUser·p0.95:   6.439 ms/op
                 listUser·p0.99:   9.028 ms/op
                 listUser·p0.999:  19.192 ms/op
                 listUser·p0.9999: 24.361 ms/op
                 listUser·p1.00:   25.854 ms/op

Iteration   3: 4.804 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.609 ms/op
                 listUser·p0.50:   4.686 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   8.126 ms/op
                 listUser·p0.999:  16.777 ms/op
                 listUser·p0.9999: 17.929 ms/op
                 listUser·p1.00:   18.285 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 196930
  mean =      4.868 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 148986 
    [ 5.000,  7.500) = 43682 
    [ 7.500, 10.000) = 3094 
    [10.000, 12.500) = 299 
    [12.500, 15.000) = 285 
    [15.000, 17.500) = 254 
    [17.500, 20.000) = 132 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.434 ms/op
     p(50.0000) =      4.694 ms/op
     p(90.0000) =      5.349 ms/op
     p(95.0000) =      5.890 ms/op
     p(99.0000) =      8.634 ms/op
     p(99.9000) =     19.464 ms/op
     p(99.9900) =     25.274 ms/op
     p(99.9990) =     26.977 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.709 ± 3.566  ops/ms
ClientPb.existUser                       thrpt       3   8.403 ± 2.615  ops/ms
ClientPb.getUser                         thrpt       3   7.833 ± 3.536  ops/ms
ClientPb.listUser                        thrpt       3   6.713 ± 1.646  ops/ms
ClientPb.createUser                       avgt       3   4.081 ± 0.489   ms/op
ClientPb.existUser                        avgt       3   3.879 ± 0.821   ms/op
ClientPb.getUser                          avgt       3   3.995 ± 0.730   ms/op
ClientPb.listUser                         avgt       3   4.846 ± 1.906   ms/op
ClientPb.createUser                     sample  225901   4.248 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.522           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.010           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.948           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.661           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.028           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.764           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.783           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.128           ms/op
ClientPb.existUser                      sample  244703   3.924 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.153           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.772           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.325           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.727           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.774           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.908           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.838           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.837           ms/op
ClientPb.getUser                        sample  236010   4.067 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.767           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.924           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.497           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.841           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.406           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.133           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.213           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.852           ms/op
ClientPb.listUser                       sample  196930   4.868 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.434           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.694           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.349           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.890           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.634           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.464           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.274           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.263           ms/op
